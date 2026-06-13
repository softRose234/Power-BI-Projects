# Power BI Advanced DAX - Cookies Sales Analysis

**Advanced Analytics & Complex Calculations on Cookie Sales Data**

---

## Introduction

This project presents a professional and comprehensive Power BI report focused on **Cookies Sales Analysis**, developed using advanced Data Analysis Expressions (DAX). While basic DAX functions can provide simple totals and averages, they are often insufficient for answering complex business questions such as “How are sales trending compared to the same period last year?”, “Which cookie variants are driving the majority of revenue?”, or “What is the cumulative performance of products throughout the year?”. 

To address these challenges, this project leverages sophisticated DAX techniques including time intelligence functions, context transition, dynamic calculations, variables for performance optimization, and advanced iterator functions. These techniques enable the creation of flexible, accurate, and high-performing measures that go far beyond standard aggregations. The resulting dashboard provides deep visibility into sales performance, product contribution, seasonal trends, and customer purchasing behavior.

---

## Tools Used

- **Microsoft Power BI Desktop** — Main platform for building the interactive report and data model
- **DAX (Data Analysis Expressions)** — Used for all advanced calculations and measures
- **Power Query Editor** — Data cleaning, transformation, and modeling
- **Variables (VAR)** — Applied for improved code readability and performance optimization
- **Professional Theme** — CY25SU12 modern theme for clean and consistent visual design

---

## Objective

The objective of this project is to build a comprehensive analytics solution for cookie sales data while showcasing advanced DAX capabilities. 

Specific goals include:
- Analyzing sales trends, seasonality, and performance across different cookie products
- Implementing complex time intelligence and comparative calculations
- Creating dynamic and reusable measures using advanced DAX techniques
- Demonstrating best practices in writing efficient and scalable DAX code
- Delivering clear, interactive visualizations that support business insights

---

## Overview of Work

The report is a multi-page Power BI dashboard built on cookie sales data. It applies advanced DAX to uncover meaningful patterns and metrics.

Key features of the report include:
- **Advanced Time Intelligence** — Year-over-Year comparisons, running totals, and moving averages
- **Product Performance Analysis** — Breakdown by cookie type/flavor with ranking and contribution analysis
- **Dynamic Calculations** — Using `CALCULATE`, variables, and context transition for flexible analysis
- **Trend & Seasonality Analysis** — Identification of peak periods and sales patterns
- **Interactive Visuals** — Clean charts and cards that respond dynamically to user filters
- **Professional Design** — Modern theming with clear layout and intuitive navigation

The report serves both as a functional analytics tool and a demonstration of advanced DAX techniques applied to real-world retail data.

---

## Step-by-Step Procedure

1. **Data Connection**  
   Connected to the cookie sales dataset containing transaction-level data such as date, product (cookie type), quantity, revenue, region, and other relevant fields.

2. **Data Preparation (Power Query)**  
   Cleaned the data, handled missing values, created a proper date table, and prepared supporting columns for advanced calculations.

3. **Data Modeling**  
   Built an optimized data model with relationships between sales facts and dimensions (Products, Dates, Regions, etc.).

4. **Advanced DAX Development**  
   Created complex measures using:
   - Time intelligence functions (`SAMEPERIODLASTYEAR`, `DATESYTD`, `TOTALYTD`)
   - Variables (`VAR`) for performance and readability
   - Advanced `CALCULATE` patterns with multiple filters and context transition
   - Iterator functions for granular analysis
   - Dynamic ranking and contribution measures

5. **Visualization Design**  
   Developed interactive pages with trend lines, bar charts, KPI cards, and comparative visuals that clearly present the results of the advanced DAX measures.

6. **Performance Optimization**  
   Applied DAX best practices to ensure fast calculation and smooth report performance.

7. **Testing & Validation**  
   Validated all measures against expected business logic and source data.

8. **Final Documentation**  
   Structured the report for clarity and prepared this professional README.

---

## Key Performance Indicators (KPIs)

The dashboard uses advanced DAX to calculate and display the following key metrics:

| KPI / Measure                        | Description                                      | Advanced DAX Technique Used          |
|--------------------------------------|--------------------------------------------------|--------------------------------------|
| **Total Revenue**                    | Overall sales revenue from cookie products       | Basic + Advanced aggregations        |
| **Year-over-Year Growth**            | Sales comparison with previous year              | Time Intelligence + `CALCULATE`      |
| **Running Total (YTD)**              | Cumulative sales throughout the year             | `TOTALYTD` and running total patterns|
| **Top Products by Revenue**          | Ranking of best-selling cookie types             | Dynamic Ranking + `RANKX`            |
| **Average Order Value**              | Average revenue per transaction                  | Iterator functions + Variables       |
| **Monthly/Seasonal Trends**          | Sales patterns over time                         | Time Intelligence + Moving Averages  |
| **Product Contribution %**           | Share of total revenue by cookie type            | `CALCULATE` + Context Transition     |
| **Previous Period Comparison**       | Flexible prior period analysis                   | Advanced time intelligence           |

These metrics are presented through interactive visuals and allow users to filter by date, product, region, or other dimensions.

---

## Conclusion

This **Power BI Advanced DAX - Cookies Sales Analysis** project demonstrates strong proficiency in writing complex and efficient DAX code within Microsoft Power BI. 

By applying advanced techniques such as time intelligence, variables, context transition, and dynamic calculations to cookie sales data, the report delivers meaningful insights while showcasing professional-grade analytical development skills. The project highlights the ability to go beyond basic measures and build scalable, high-performance solutions that provide real business value in retail and consumer analytics.

---


---

*This project is part of my professional portfolio demonstrating advanced Power BI and DAX development skills.*
