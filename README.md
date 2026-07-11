# ✈️ Flight Delay and Cancellation Analysis

An end-to-end aviation analytics dashboard built in Power BI, designed on a **Star Schema data model** for optimized performance and clean, scalable reporting.

🔗 **[Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzFkZGJhNzYtMjg5OC00YTNlLWIxODctMTQ1NTljZTRmNDFkIiwidCI6ImUxNGU3M2ViLTUyNTEtNDM4OC04ZDY3LThmOWYyZTJkNWE0NiIsImMiOjEwfQ%3D%3D)**

---

## 📌 Overview

This project analyzes **300K+ flight records** spanning **10+ years**, across multiple airlines, hundreds of airports, and 6+ delay categories, to uncover the key operational factors driving flight delays and cancellations.

## 📂 Dataset

- **Source:** Kaggle — [Airline Delay Cause Dataset](https://lnkd.in/guM_FM5T)

## 🔹 Data Modeling

- Implemented a **Star Schema** with 1 fact table and 3 dimension tables (Time, Airline, Airport).
- Improved query performance and slicer interactions across 300K+ records.
- Used an industry-aligned modeling approach standard in BI teams.

## 🔹 Key Insights Delivered

- Flight delay and cancellation trends across years and months.
- Root cause analysis: Carrier, Weather, NAS, Late Aircraft.
- Airline-wise and airport-wise performance comparison.
- Identification of high-risk airports with maximum delay percentages.

## 🔹 Dashboards

- **Page 1:** Flight Delay & Cancellation Overview (KPIs, city & airline analysis)
- **Page 2:** Delay Trends & Root Cause Analysis (yearly, monthly & airport insights)

## 🔹 Skills Demonstrated

`Power BI` · `Star Schema` · `DAX` · `Data Modeling` · `Power Query` · `SQL`
`KPI Design` · `Interactive Slicers` · `Business-Focused Visuals`

---
📊 Data Model

             ### ┌─────────────────┐
                 │   Dim_Time      │
                 └────────┬────────┘
                          │
┌─────────────────┐      │      ┌─────────────────┐
│  Dim_Airline     ├──────┼──────┤   Dim_Airport   │
└─────────────────┘      │      └─────────────────┘
                          │
                 ┌────────┴────────┐
                 │  Fact_Flights   │
                 │  (300K+ rows)   │
                 └─────────────────┘


This project simulates real-world airline operations analytics used for performance monitoring and decision-making.

## 📎 Links

- 🔗 [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzFkZGJhNzYtMjg5OC00YTNlLWIxODctMTQ1NTljZTRmNDFkIiwidCI6ImUxNGU3M2ViLTUyNTEtNDM4OC04ZDY3LThmOWYyZTJkNWE0NiIsImMiOjEwfQ%3D%3D)
- 💻 [GitHub Repo](https://github.com/Geethika-pamidi/Flight-Delay-Cancellation-Analysis)
