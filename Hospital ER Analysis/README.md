# Hospital Emergency Room (ER) Analytics Dashboard

**Power BI Project | Healthcare Operations Intelligence**

---

## Introduction

Emergency Room (ER) operations are among the most critical and time-sensitive areas in any hospital. Efficient patient flow, timely triage, and optimal resource utilization directly impact patient outcomes, satisfaction, and overall hospital performance. 

This project delivers a comprehensive, interactive **Hospital ER Analytics Dashboard** built in Microsoft Power BI. The dashboard transforms raw ER operational data into clear, actionable insights, enabling hospital administrators, department heads, and healthcare professionals to monitor performance, identify bottlenecks, and make data-driven decisions to improve service delivery.

---

## Tools Used

- **Microsoft Power BI Desktop** — Core platform for data modeling, visualization, and interactive report development
- **Power Query Editor** — Data extraction, cleaning, transformation, and loading (ETL)
- **DAX (Data Analysis Expressions)** — Advanced calculations, custom measures, and time intelligence
- **Power BI Visualizations** — KPI cards, line charts, bar charts, pie/donut charts, tables, and slicers
- **Professional Theming** — Applied modern theme (CY25SU12) for consistent, clean, and executive-ready design

---

## Objective

The primary objective of this project is to develop a professional-grade analytics solution that provides real-time visibility into ER performance. Specific goals include:

- Tracking patient volume, wait times, and flow efficiency
- Analyzing triage processes and resource utilization
- Identifying peak periods and operational bottlenecks
- Supporting data-driven staffing, process improvement, and strategic decision-making
- Enhancing patient experience and hospital operational excellence through actionable insights

---

## Overview of Work

The Hospital ER Analysis dashboard is a multi-page, fully interactive Power BI report designed for both high-level overviews and detailed analysis. 

Key features include:
- **KPI Cards** displaying critical metrics at a glance
- **Trend Analysis** showing performance patterns over time (hourly, daily, weekly, monthly)
- **Distribution Visuals** (pie, donut, and bar charts) for triage levels, patient categories, and outcomes
- **Comparative Analysis** across shifts, days of the week, and time periods
- **Interactive Filters & Slicers** enabling dynamic exploration by date range, triage category, department, and other dimensions
- **Professional Design** with clean layout, consistent theming, responsive visuals, and intuitive navigation

The report leverages a wide range of Power BI visualization types to present complex healthcare data in an accessible and executive-friendly format.

---

## Step-by-Step Procedure

1. **Data Connection**  
   Connected to the hospital ER dataset containing patient arrival records, triage timestamps, treatment durations, admission/discharge details, and resource information.

2. **Data Transformation (Power Query)**  
   Cleaned and prepared the data by handling missing values, standardizing date/time formats, removing duplicates, and creating calculated columns such as Wait Time, Length of Stay, and Time-based dimensions.

3. **Data Modeling**  
   Built a star-schema data model with proper relationships between fact tables (Visits) and dimension tables (Patients, Time, Triage Levels, Resources, Outcomes) to ensure efficient and accurate analysis.

4. **DAX Development**  
   Created robust measures and calculations including:
   - Total ER Visits
   - Average Wait Time
   - % Patients Admitted
   - Average Length of Stay
   - Peak Hour Analysis using time intelligence functions

5. **Visualization & Dashboard Design**  
   Designed multiple report pages with KPI cards, trend lines, comparative charts, and distribution visuals. Applied professional formatting, conditional formatting, and interactive elements (slicers, drill-through, bookmarks).

6. **Theming & Polish**  
   Applied the modern CY25SU12 theme for visual consistency. Ensured responsive design, clear titles, and user-friendly navigation suitable for healthcare stakeholders.

7. **Testing & Validation**  
   Validated all measures and visuals against source data for accuracy. Optimized report performance and responsiveness.

8. **Documentation**  
   Prepared this professional README to document the project methodology, tools, and outcomes.

---

## Key Performance Indicators (KPIs)

The dashboard tracks the following essential ER performance metrics:

| KPI                          | Description                                      | Business Value |
|-----------------------------|--------------------------------------------------|--------------|
| **Total ER Visits**         | Total number of patients visiting the ER         | Measures demand and operational volume |
| **Average Wait Time**       | Average time from patient arrival to first assessment | Critical indicator of patient experience and care quality |
| **Admission Rate**          | Percentage of ER patients admitted to the hospital | Reflects case severity and downstream resource needs |
| **Average Length of Stay**  | Average duration patients spend in the ER        | Helps identify treatment bottlenecks |
| **Triage Level Distribution** | Breakdown of patients by urgency categories     | Assesses case mix and resource planning |
| **Peak Period Analysis**    | Visits and wait times by hour/day of week        | Supports optimal staffing and scheduling |

These KPIs are presented through interactive cards, trend visuals, and detailed breakdowns, allowing users to filter and drill down for targeted insights.

---

## Conclusion

This Hospital ER Analytics Dashboard project demonstrates the effective application of Microsoft Power BI in the healthcare domain. By converting complex operational data into clear, interactive visualizations and key performance metrics, the dashboard enables hospital leadership to monitor ER performance, reduce wait times, optimize resource allocation, and ultimately improve patient care and operational efficiency.

The project showcases strong capabilities in data modeling, DAX development, professional dashboard design, and healthcare analytics — skills that are highly valuable for data-driven decision-making in the healthcare industry.

---



---


