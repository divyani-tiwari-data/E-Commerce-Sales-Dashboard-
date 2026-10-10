# E-Commerce Sales Dashboard

## Project Overview
An interactive Power BI dashboard designed to analyze e-commerce sales performance, track core business metrics ($1.57M Sales, $175K Net Profit, 22K Orders), and identify margin leakages across product categories and regions.

---

## Short Description
This report provides a single-page operational view to evaluate sales and profit trends (2019 vs 2020), identify loss-making products, analyze customer shipping preferences, and monitor region-wise performance.

---

## Tech Stack
* Power BI Desktop: Used as the core business intelligence platform to design interactive layouts and visual reports.
* Power Query: Utilized for data cleaning, transformation, and shaping raw transactional CSV files.
* Calculated Measures: Applied basic DAX formulas to create key metrics (Sales, Profit, Orders, AOV).
* Data Architecture: Single-table transactional data model focused on clean presentation and smooth usability.

---

## Data Source
* Dataset Name: E-Commerce Sales Dataset (Kaggle - Superstore Sales Dataset)
* Access Link: [Download Dataset CSV](https://drive.google.com/file/d/15I8Xe_XJoz_vaMoCE8PAt-OJ40m9uSIw/view?usp=drivesdk)
* Key Attributes: Order ID, Sales, Profit, Quantity, Customer Segment, Region, State, Category, Sub-Category, Ship Mode, and Payment Mode.


---

## Features & Highlights

### Business Problem & Key Questions
E-commerce operations struggle to pinpoint profit leakage and cost drivers across thousands of orders. Key questions addressed:
* Which specific products are causing significant profit losses despite high sales volume?
* What payment methods (COD, Online, Cards) drive the highest transaction share?
* How do monthly revenue and profit trends compare between 2019 and 2020?
* Which shipping modes are most frequently selected by customers?

---

### Walkthrough of Key Visuals
* **Top KPI Cards:** Direct view of Orders (**22K**), Revenue (**$1.57M**), Net Profit (**$175K**), and AOV (**$70**).
* **Filters & Slicers:** Top slicers for **Furniture**, **Office Supplies**, and **Technology** for dynamic filtering.
* **Charts & Maps:** Geographic sales map, monthly YoY trend lines, and payment/shipping distribution visuals.
* **Performance Bars:** Category/Sub-category breakdown and **Bottom 5 Products by Profit** visualization.

---

### Key Business Insights
* **Profit Bleed Alert:** Clear margin bleed identified in **Bottom 5 Products**, where Cubify 3D printers record heavy negative profits down to **-$6.2K**.
* **Payment & Shipping Trends:** **Cash on Delivery ($667.42K)** dominates payment methods, while customers heavily prefer **Standard Class ($912.4K)** shipping over express options.
* **Regional & Category Leadership:** **Office Supplies ($643.71K)** is the highest revenue category, and the **West Region ($522.33K)** leads regional contributions.
* **YoY Trends:** Tracked monthly sales and profit growth performance comparing 2019 vs 2020.

## Dashboard Preview

![E-Commerce Sales Dashboard](Snapshot%20of%20the%20Dashboard.png)
