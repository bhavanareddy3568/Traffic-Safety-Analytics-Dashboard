# Traffic-Safety-Analytics-Dashboard
An end-to-end traffic safety analytics solution built in Microsoft Excel. Features multi-year data aggregation (2011–2015) of Florida Highway Patrol (FHP), trend &amp; ratio analysis, and an interactive executive dashboard visualizing KPIs, incident distributions, and growth metrics to drive data-backed safety insights.

# Comprehensive Traffic Crash & Safety Analysis Dashboard (2011–2015)

## 📌 Project Overview
This project delivers an end-to-end data analysis and interactive dashboard solution using a multi-year traffic accident dataset. The objective was to aggregate, analyze, and visualize five years of traffic data to identify long-term safety trends, evaluate the relationship between different crash types, and calculate critical key performance indicators (KPIs) regarding injury and fatality rates.

The final portfolio item demonstrates advanced data manipulation, dynamic ratio calculations, and executive-level dashboard design within Microsoft Excel.

## 📊 Key Insights & Analytical Findings
Based on the structured business questions addressed during this analysis, the data reveals several critical trends:

* **Consistent Growth in Traffic Incidents:** Total crashes have exhibited a strict **linear increase** over time, surging by **63.17%** from 229,210 in 2011 to 374,003 in 2015.
* **Injury vs. Crash Trends:** While total crashes grew by over 63%, injury crashes and total injuries grew at a slightly slower, parallel linear rate (~35% and ~33.6% respectively). This indicates that while accidents are increasing rapidly, severity management or vehicle safety features may be helping cap the injury growth rate.
* **Commercial Vehicle Surge:** A massive outlier in the growth metrics is **Commercial Vehicle Crashes**, which skyrocketed by **233.35%** over the 5-year period, indicating a major areas of focus for commercial transit safety enforcement.
* **Fatality Dynamics:** Crashes involving traffic fatalities grew by **20.54%**. The portfolio maps these proportions using dedicated distribution graphs to compare absolute crash volume against fatal outcomes.

---

## 🛠️ Data Architecture & Workbook Structure
The underlying workbook (`FHP_Crash_Data_Analysis.xlsx`) is structured into a production-ready data pipeline split across specialized sheets:

1.  **Yearly Data Sheets (2011–2015):** Contains the cleaned, foundational historical records.
2.  **Data (Summary Sheet):** The core analytical engine. It handles cross-sheet aggregations, compiles time-series metrics, evaluates absolute differences, and utilizes integrated **Sparklines** for immediate, inline trend recognition.
3.  **Questions:** The logical framework mapping core business/safety questions to specific data models, mathematical ratios (e.g., a Total-to-Injury Crash ratio of **1.46**), and visual graph selections.
4.  **Dashboard:** The presentation layer containing targeted KPIs (Crashes, Injuries, Fatalities), Pie Charts comparing injury vs. total crashes, Doughnut Graphs evaluating fatality distribution ratios, and Time-Series trend charts.

---

## 📈 Dashboard Preview
!(IMAGES/FHP_dashboard.png)<img width="1500" height="735" alt="FHP_Dashboard" src="https://github.com/user-attachments/assets/f1aa6956-f8ba-453c-9eda-db4085019378" />


---

## 🧠 Solved Analytical Questions

| Business / Safety Question | Analytical Method / Visual Asset | Core Finding / Resolution |
| :--- | :--- | :--- |
| **How have total crashes changed over time?** | Time-Series Linear Trendline | Steady, linear upward growth (~63.2% total increase). |
| **Are injuries increasing at the same rate as crashes?** | Dual-Axis Trend Chart | Yes, showing parallel linear growth but at a lower velocity. |
| **What is the total crashes to injury crashes ratio?** | Ratio Formula Model | **1.46** (For every ~1.46 crashes, 1 results in an injury). |
| **Which category contributes most to volume?** | Distribution Analysis | **Property Damage Crashes** dominate absolute volume; **Crashes with Traffic Fatalities** dominate severity metrics. |
| **What is the fatality/injury rate per crash?** | Distribution Doughnut & Pie Charts | Visualized across categories to isolate high-risk crash types (e.g., Pedestrian/Bicycle vs. Vehicle). |

---

## ⚡ Tech Stack & Skills Demonstrated
* **Advanced Data Aggregation:** Summary formulation across multi-sheet workbooks.
* **Descriptive Statistics:** Calculating percentage change, ratios, totals, and differences over time.
* **Data Visualization:** Designing intuitive executive dashboards utilizing KPI blocks, Sparklines, customized Pie Charts, Doughnut Charts, and Linear Trendlines.
