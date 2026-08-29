# Retail Sales Performance Analysis – Excel

An interactive Excel dashboard analyzing 8,400+ retail orders to uncover profit, sales, and operational trends across regions, customer segments, product categories, and time periods.

![Sales Analysis Dashboard](images/dashboard_screenshot.png)

## Overview

This project takes a raw retail orders dataset and turns it into a decision-ready dashboard using Excel Pivot Tables and Pivot Charts — the kind of quick-turnaround analysis a business stakeholder would ask for to understand where sales and profit are coming from.

## Dataset

- **Source file:** `Orders_Dataset.csv` (also available inside `Retail_Sales_Dashboard.xlsx` on the **Orders** sheet)
- **Size:** ~8,400 orders
- **Fields:** Order ID, Order Date, Order Priority, Order Quantity, Sales, Discount, Selling Price, Shipping Cost, Profit, Ship Mode, Customer Name, Province, Region, Customer Segment, Product Category/Sub-Category/Name, Product Base Margin, Ship Date, Day Name, Year

The workbook also includes a lookup table (**Other Info** sheet) mapping Region Codes to Region names/managers, and Customer Segment IDs to segment names — used to keep the raw data normalized before analysis.

## Tools Used

- Microsoft Excel — Pivot Tables, Pivot Charts, Dashboard design

## What the Dashboard Answers

- **Profit by Region** — which regions generate the most profit
- **Profit by Customer Segment** — Corporate vs. Consumer vs. Home Office vs. Small Business profitability
- **Sales by Year (2009–2012)** — year-over-year sales trend
- **Average Days to Pack by Product Sub-Category** — where fulfillment is slower
- **Daily Sales Trend (Sun–Sat)** — which days drive the most order volume
- **Weekday vs. Weekend Sales** — total sales split by day type

## Key Findings

- **Corporate is the most profitable segment** (~$599.7K), nearly double the Consumer segment (~$288K) despite likely lower order counts — suggesting Corporate deals carry higher margins.
- **East region leads on profit** (~$369K) even though it's not necessarily the highest-volume region — worth investigating pricing or product mix driving this.
- **Weekdays drive ~70% of total sales** (~$10.9M) vs. weekends (~$4.7M), which makes sense for a B2B-leaning customer base like Corporate/Small Business.
- **2009 was the strongest sales year** (~$4.38M) with a gradual decline through 2011, before a slight recovery in 2012 — worth a deeper trend investigation.

## Repository Structure

```
├── Retail_Sales_Dashboard.xlsx   # Full workbook: raw data, lookup tables, pivot tables, dashboard
├── Orders_Dataset.csv            # Raw orders dataset (for quick preview/reuse)
├── images/
│   └── dashboard_screenshot.png  # Dashboard preview
└── README.md
```

## Next Steps

This is being extended into a full **Excel + EDA** version, adding:
- Data cleaning documentation (nulls, duplicates, outlier checks)
- Descriptive statistics (mean/median/std dev by category)
- Discount-vs-profit and priority-vs-shipping-cost relationship analysis
- A written findings & recommendations summary

---
**Author:** Rakada Rupesh Nagireddy | [GitHub](https://github.com/Rupesh-29) | [LinkedIn](https://www.linkedin.com/in/rakada-rupesh)
