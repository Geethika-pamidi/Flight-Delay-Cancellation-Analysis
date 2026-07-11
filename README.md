✈️ Flight Delay and Cancellation Analysis

An end-to-end aviation analytics dashboard built in Power BI, designed on a **Star Schema data model** for optimized performance and clean, scalable reporting.

🔗 **[Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzFkZGJhNzYtMjg5OC00YTNlLWIxODctMTQ1NTljZTRmNDFkIiwidCI6ImUxNGU3M2ViLTUyNTEtNDM4OC04ZDY3LThmOWYyZTJkNWE0NiIsImMiOjEwfQ%3D%3D)**

---

📌 Overview

This project analyzes **300K+ flight records** spanning **10+ years**, across multiple airlines, hundreds of airports, and 6+ delay categories, to uncover the key operational factors driving flight delays and cancellations.

## 🚀 What I Built

- Designed and developed an interactive Power BI dashboard analyzing 300K+ flight records to enable data-driven operational insights.
- Implemented an optimized **Star Schema** data model — 1 fact table and 3 dimension tables (Time, Airline, Airport) — improving report performance and ensuring accurate aggregations at scale.
- Performed Exploratory Data Analysis (EDA) and tracked **15+ KPIs** (total flights, delay rate, cancellation rate, delay minutes by cause).
- Identified major delay drivers — carrier, weather, NAS, and late aircraft — highlighting key operational bottlenecks.

## 🛠️ Tools & Technologies

`Power BI Desktop` · `Power Query` · `DAX` · `Data Modeling (Star Schema)` · `SQL`

## 📊 Data Model

```
                 ┌─────────────────┐
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
```

## 📈 Key Insights

- Carrier, weather, NAS, and late aircraft are the top contributors to flight delays.
- Delay and cancellation patterns vary significantly by airport and season.
- The Star Schema model kept dashboard queries fast even at 300K+ record scale.

## 📎 Links

- 🔗 [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzFkZGJhNzYtMjg5OC00YTNlLWIxODctMTQ1NTljZTRmNDFkIiwidCI6ImUxNGU3M2ViLTUyNTEtNDM4OC04ZDY3LThmOWYyZTJkNWE0NiIsImMiOjEwfQ%3D%3D)
- 💻 [GitHub Repo](https://github.com/Geethika-pamidi/Flight-Delay-Cancellation-Analysis)
