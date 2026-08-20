# 📊 E-Commerce Sales Dashboard

## 📌 Project Overview
A dynamic, interactive Power BI report designed to analyze sales performance, customer purchasing behavior, order metrics, and key profitability drivers across regions and product categories.

---

## 📌 Short Description / Purpose
The **E-commerce Sales Dashboard** is an analytical visual tool built to help e-commerce businesses track performance KPIs, evaluate profit margins, and optimize inventory and marketing strategies. This dashboard provides actionable insights into sales trends, payment method preferences, top-performing categories, and state-wise customer distribution, enabling data-driven decision-making for business growth.

---

## 🛠️ Tech Stack
* 📊 **Power BI Desktop:** Main data visualization platform used for report creation and interactive dashboard design.
* 📂 **Power Query:** Data transformation, cleaning, and ETL layer used for reshaping raw e-commerce data.
* 🧠 **DAX (Data Analysis Expressions):** Used to compute key calculated measures, YoY growth, margins, and dynamic visual filters.
* 📝 **Data Modeling:** Star schema modeling established between sales data, customer demographics, and product lookup tables to enable seamless cross-filtering.

---

## 📂 Data Source
* **Source:** E-commerce Transactional Dataset (Sales, Orders, Details, and Customer Attributes).
* **Dataset Scope:** Contains detailed records of customer transactions, order quantities, sales amounts, profit margins, payment modes, product sub-categories, and geographic delivery locations.

---

## 🚀 Features & Highlights

### 🎯 Business Problem
E-commerce businesses process thousands of transactions daily across various product categories and geographic locations. Without a centralized analytical view, stakeholders struggle to answer critical questions quickly:
* Which product categories drive the highest revenue versus profit margin?
* Who are the top customers, and what are their buying patterns?
* Which regions or states are underperforming in sales?
* What payment methods are most preferred by customers?

### 🎯 Goal of the Dashboard
To deliver an end-to-end interactive report that:
* Monitors real-time business health using core financial KPIs (Sales, Profit, Quantity, AOV).
* Identifies top revenue-generating product lines and profit-draining categories.
* Maps regional sales distribution to help target local marketing and logistics.

---

### 📈 Walkthrough of Key Visuals

* **Key KPIs (Top Summary Cards):**
  * **Total Sales Amount:** Overall revenue generated.
  * **Total Profit:** Net profit realized across orders.
  * **Total Quantity Sold:** Number of units shipped.
  * **Average Order Value (AOV):** Revenue performance per customer transaction.

* **Category & Sub-Category Performance (Bar Chart):**
  * Ranks product lines (e.g., Clothing, Electronics, Furniture) by total revenue and profit margins to highlight bestsellers.

* **Sales by State / Region (Map & Horizontal Bar Visual):**
  * Visualizes geographical performance across different states, identifying key revenue hotspots and low-performing markets.

* **Payment Mode Breakdown (Donut Chart):**
  * Displays customer preference across Cash on Delivery (COD), Credit Card, UPI, and EMI transactions.

* **Monthly Sales & Profit Trend (Line / Combo Chart):**
  * Tracks month-over-month sales velocity to identify seasonal spikes and sales dips throughout the fiscal year.

---

## 💡 Key Business Insights (From Dashboard)
* **Payment Preference:** Cash on Delivery (COD) leads sales at **$667.42K**, closely followed by Online Payments (**$553.59K**).
* **Regional & Segment Lead:** The **West Region ($522.33K)** is the highest revenue generator, and the **Consumer Segment ($730K+)** drives the bulk of total orders.
* **Shipment Method:** **Standard Class** is the most preferred shipping mode (**$912.4K**), indicating customers prefer lower shipping costs over same-day delivery.
* **Profit Bleed Alert:** The **Bottom 5 Products by Profit** visual highlights items causing significant net losses (e.g., Cubify products with negative margins up to **-$6.2K**), requiring urgent pricing adjustments.

---

## 📸 Dashboard Preview

![E-commerce Sales Dashboard](YOUR_IMAGE_LINK_HERE)
