# E-Commerce Sales Dashboard

## Project Overview
A dynamic, interactive Power BI report designed to analyze sales performance, customer purchasing behavior, order metrics, and key profitability drivers across regions and product categories.

---

## Short Description / Purpose
The E-commerce Sales Dashboard is an analytical visual tool built to help e-commerce businesses track performance KPIs, evaluate profit margins, and optimize inventory and marketing strategies. This dashboard provides actionable insights into sales trends, payment method preferences, top-performing categories, and state-wise customer distribution, enabling data-driven decision-making for business growth.

---

## Tech Stack
* Power BI Desktop: Used as the core business intelligence and data visualization platform to design, build, and publish interactive analytics dashboards.
* Power Query: Utilized for data extraction, transformation, and loading (ETL), enabling data cleaning, shape transformation, and column manipulation.
* DAX (Data Analysis Expressions): Applied to write optimized formulas and calculated measures for dynamic data analysis, aggregations, and performance metrics.

---

## Data Source
* Source: Kaggle (Superstore Sales Dataset)
* Format: CSV (.csv)
* Dataset Scope: Contains transactional records including Order ID, Order Date, Ship Mode, Customer Segment, Region, State, Category, Sub-Category, Sales, Quantity, Discount, and Profit.

---

## Features & Highlights

### Business Problem
E-commerce businesses process thousands of transactions daily across various product categories and geographic locations. Without a centralized analytical view, stakeholders struggle to answer critical questions quickly:
* Which product categories drive the highest revenue versus profit margin?
* Who are the top customers, and what are their buying patterns?
* Which regions or states are underperforming in sales?
* What payment methods are most preferred by customers?

---

### Goal of the Dashboard
To deliver an end-to-end interactive report that:
* Monitors real-time business health using core financial KPIs (Sales, Profit, Quantity, AOV).
* Identifies top revenue-generating product lines and profit-draining categories.
* Maps regional sales distribution to help target local marketing and logistics.

---

### Walkthrough of Key Visuals
* Top KPI Summary Cards: Instant visibility into core metrics—**Total Orders (22K)**, **Revenue ($1.57M)**, **Net Profit ($175K)**, and **Average Order Value ($70)**.
* Sales by Region & State: Donut and Map visuals to track geographical distribution, highlighting the **West Region ($522.33K)** as the top revenue contributor.
* Payment Mode & Segment Analysis: Donut charts breaking down customer buying choices, showing **Cash on Delivery ($667.42K)** and the **Consumer Segment ($730K+)** as primary drivers.
* Monthly Sales & Profit Trends by Year: Line charts comparing performance over time **(2019 vs 2020)** to track seasonality and growth patterns.
* Shipping & Product Performance: Bar charts analyzing sales across shipping modes (**Standard Class leading at $912.4K**) and pinpointing performance by Category, Sub-Category, and **Bottom 5 Loss-Making Products**.

---

## Key Business Insights (From Dashboard)
* Payment Preference: **Cash on Delivery (COD)** leads sales at **$667.42K**, closely followed by **Online Payments ($553.59K)**.
* Regional & Segment Lead: The **West Region ($522.33K)** is the highest revenue generator, and the **Consumer Segment ($730K+)** drives the bulk of total orders.
* Shipment Method: **Standard Class** is the most preferred shipping mode (**$912.4K**), indicating customers prefer lower shipping costs over same-day delivery.
* Profit Bleed Alert: The **Bottom 5 Products by Profit** visual highlights items causing significant net losses (e.g., Cubify products with negative margins up to **-$6.2K**), requiring urgent pricing adjustments.

---

## Dashboard Preview

![E-commerce Sales Dashboard](Snapshot%20of%20the%20Dashboard.jpeg)
