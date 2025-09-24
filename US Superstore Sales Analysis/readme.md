
---

# 📊 US Superstore Sales Dashboard - README

## 📌 Introduction

The **US Superstore Sales Dashboard** is a comprehensive business intelligence report designed to provide insights into sales performance across various metrics, products, and regions. This dashboard compares performance between **January 1, 2023 - December 31, 2024** and the **Same Period Last Year (SPLY)**, helping stakeholders monitor growth, identify trends, and make data-driven decisions.

---

## 🛠️ Tools Used

* **Power BI**
  Power BI was used to build this interactive and dynamic sales dashboard. It provides rich visualization capabilities, easy data transformation using Power Query, and DAX formulas for custom metrics.

---

## 📈 Key Performance Indicators (KPIs)

The dashboard focuses on the following KPIs:

| KPI               | Value    | YoY Change | SPLY Value |
| ----------------- | -------- | ---------- | ---------- |
| **Revenue**       | \$226.2M | +108.85%   | \$107.51M  |
| **Quantity Sold** | 2M Units | +102.26%   | 1M Units   |
| **Profit**        | \$50M    | +108.85%   | \$24M      |
| **Orders**        | 1,000    | +106.87%   | 655        |
| **Gross Profit**  | 22.13%   | -          | -          |
| **Products Sold** | 6        | -          | -          |
| **Countries**     | 5        | -          | -          |

---

## 📊 Dashboard Sections Overview

### 1. **Top Summary Cards**

Displays the key KPIs like Revenue, Profit, Orders, Quantity Sold, and percentage growth compared to SPLY.

### 2. **Monthly Trend (Profit/Revenue by Month)**

Line graph showing monthly performance trends to track seasonal spikes or dips in revenue/profit.

### 3. **Country-wise Breakdown**

* **Profit by Country** (Top half)
* **Revenue by Country** (Bottom half)
  Shows performance distribution across Canada, France, Germany, Mexico, and the USA.

### 4. **Product Analysis**

* **Profit by Product**
* **Revenue by Product**
* **Units Sold by Product**
* **Discounts by Product**
  Helps in identifying the best-performing products and those with high discounts.

---

## 🧭 Step-by-Step Procedure to Build the Dashboard

### 1. **Data Collection**

Import sales data from a structured source like Excel, SQL Server, or cloud storage containing:

* Orders
* Products
* Revenue
* Country
* Discounts

### 2. **Data Cleaning & Transformation (Power Query)**

* Remove duplicates
* Format date columns
* Create calculated columns for SPLY comparison
* Filter data for relevant time frames

### 3. **Data Modeling**

* Create relationships between tables: Products, Sales, Customers, Regions, Time
* Create Date table for time intelligence functions

### 4. **DAX Calculations**

Define KPIs using DAX, for example:

```DAX
Total Revenue = SUM(Sales[Revenue])
YoY Growth = DIVIDE([This Year Revenue] - [Last Year Revenue], [Last Year Revenue])
Gross Profit % = DIVIDE([Profit], [Revenue])
```

### 5. **Visualization**

Use the following visual elements:

* **Card visuals** for KPIs
* **Line Charts** for monthly trends
* **Bar Charts** for product and country breakdowns
* **Slicers** to switch between Profit and Revenue views

### 6. **Interactivity & Filters**

* Add slicers for year, product, and metric type (Profit/Revenue)
* Use bookmarks to toggle between views
* Ensure visuals are interconnected for dynamic filtering

### 7. **Formatting & Design**

* Apply consistent color themes (blue/white for clarity)
* Use data labels, legends, and tooltips for better understanding
* Place logo and author name (e.g., *Awokojo Kehinde*) for branding

---

## ✅ Conclusion

The **US Superstore Sales Dashboard** is a powerful tool for tracking business growth and performance across multiple dimensions. By leveraging **Power BI**, this dashboard offers:

* A holistic view of sales metrics
* Insights into product and regional performance
* Year-over-year comparison to evaluate growth

This enables sales teams, executives, and analysts to make better strategic decisions backed by real data.

---

## 📂 File Details

* **Dashboard Title:** US Superstore Sales Dashboard
* **Author:** Cletus Rosemary 
* **Tool:** Power BI
* **Comparison Period:** Jan 01, 2023 - Dec 31, 2024 vs SPLY

---



