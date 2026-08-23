# E-Commerce Sales Dashboard

## Project Overview
An interactive Power BI dashboard created using Kaggle's Superstore Sales Dataset to track key metrics—$1.57M in Total Sales, $175K in Net Profit, and 22K Total Orders—across regions, categories, and customer segments.

---

## Short Description / Purpose
This report provides a single-page operational view to evaluate sales and profit trends (2019 vs 2020), identify loss-making products, analyze customer shipping preferences, and monitor region-wise performance.

---

## Tech Stack
* Power BI Desktop: Used as the core business intelligence platform to design interactive layouts and visual reports.
* Power Query: Utilized for data cleaning, transformation, and shaping raw transactional CSV files.
* DAX (Data Analysis Expressions): Applied to write calculated measures for aggregate sales, net margins, order counts, and YoY time-intelligence comparisons.

---

## Data Source
* Source: Kaggle (Superstore Sales Dataset)
* Format: CSV (.csv)
* Key Attributes: Order ID, Sales, Profit, Quantity, Customer Segment, Region, State, Category, Sub-Category, Ship Mode, and Payment Mode.

---

## Features & Highlights

### Business Problem
E-commerce operations struggle to pinpoint profit leakage and cost drivers across thousands of orders. Key questions addressed:
* Which specific products are causing significant profit losses despite high sales volume?
* What payment methods (COD, Online, Cards) drive the highest transaction share?
* How do monthly revenue and profit trends compare between 2019 and 2020?
* Which shipping modes are most frequently selected by customers?

---

### Goal of the Dashboard
* Monitor core business performance using top-level KPI cards (**22K Orders, $1.57M Sales, $175K Profit, $70 AOV**).
* Isolate loss-draining items to enable immediate catalog or pricing intervention.
* Track category and sub-category distribution for inventory planning.

---

### Walkthrough of Key Visuals
* **Top KPI Summary Cards:** Direct view of Orders (**22K**), Revenue (**$1.57M**), Net Profit (**$175K**), and Average Order Value (**$70**).
* **Category Slicers:** Top slicers for **Furniture**, **Office Supplies**, and **Technology** for dynamic report filtering.
* **Geographic Distribution:** Map and Donut chart highlighting **West Region ($522.33K)** as top revenue driver, followed by **East ($449.75K)**, **Central ($341.97K)**, and **South ($251.75K)**.
* **Payment Mode & Segment:** Donut visuals showing **COD ($667.42K)** leading payment methods, and **Consumer ($753K)** leading customer segments.
* **YoY Monthly Trends:** Line charts mapping **2019 vs 2020** performance for both Monthly Profit and Monthly Sales.
* **Shipping & Product Performance:** Bar visuals tracking **Standard Class ($912.4K)** dominance, **Office Supplies ($643.71K)** top category sales, **Phones ($196.56K)** top sub-category, and **Bottom 5 Products by Profit** (e.g., Cubify products losing up to **-$6.2K**).

---

## Key Business Insights
* **Payment Dominance:** Cash on Delivery (COD) accounts for the largest share at **$667.42K**, followed by Online (**$553.59K**) and Cards (**$344.39K**).
* **Shipping Behavior:** Customers heavily favor **Standard Class ($912.4K)** shipping over express modes like Same Day (**$95.96K**).
* **Profit Leakage Alert:** Clear margin bleed identified in the **Bottom 5 Products**, where Cubify 3D printers record heavy negative profits down to **-$6.2K**.
* **Regional & Category Leadership:** **Office Supplies ($643.71K)** is the highest revenue category, and the **West Region ($522.33K)** leads regional contributions.

---

## Dashboard Preview

![E-Commerce Sales Dashboard](Snapshot%20of%20the%20Dashboard.jpeg)
