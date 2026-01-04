---
title: Real Estate Market Intelligence 2026
publishDate: 2026-01-04 00:00:00
img: /assets/yad2_dashboard_page-0001.jpg
img_alt: Interactive real estate dashboard showing housing market trends and KPIs
description: |
  An end-to-end data analytics solution combining Python ETL and Power BI to analyze 9,900+ property listings, focusing on benchmarks and regional demand.
tags:
  - Python
  - Power BI
  - DAX
  - Data Cleaning
  - Real Estate Analytics
---

#### Project Overview

The **Real Estate Market Intelligence** project is a comprehensive data analysis and BI solution designed to decode complex housing markets. By transforming raw, unstructured data from property portals into actionable insights, this project helps users identify "Value for Money" investment opportunities through data-driven transparency.

The project demonstrates a full data lifecycle: from handling messy text and numerical outliers in **Python** to designing a high-fidelity, interactive dashboard in **Power BI**.

---

#### Application Features

- **Dynamic KPI Tracking:** Real-time visibility into average prices, listings count, and price-per-SQM.
- **Hierarchical Market Drill-down:** Ability to filter data from a broad district level down to specific neighborhoods and streets.
- **Geographic Heatmap:** Visual identification of high-demand clusters and pricing hotspots using spatial mapping.
- **Settlement Ranking:** Comparison of different areas based on their price-per-SQM "Value Index" to identify market anomalies.

---

#### Data & ETL Process (Python)

The raw dataset was processed using **Pandas** and **NumPy** to ensure analytical integrity:
- **String Normalization:** Corrected encoding and formatting issues for proper visualization of location data across different platforms.
- **Outlier Mitigation:** Filtered out unrealistic listings (e.g., placeholder prices or incorrect area sizes) that skew market averages.
- **Feature Engineering:** Created a custom `Price per SQM` metric to serve as the primary normalized benchmark for fair comparison.

---

#### Modeling & Visualization

- **Power BI Data Model:** Built a structured star-schema to handle thousands of listings efficiently while maintaining high performance.
- **Advanced DAX:** Implemented custom measures for dynamic averages, weighted calculations, and intelligent filtering logic.
- **UI/UX Design:** Integrated a professional dark-themed sidebar for navigation, custom icon-based KPIs, and a "Quick Reset" function for seamless user exploration.

---

#### Tools & Technologies

- **Python** (Pandas, NumPy) – Data Cleaning & ETL
- **Power BI Desktop** – Data Modeling & Dashboarding
- **DAX** – Analytical Calculations
- **Jupyter Notebooks** – Exploratory Data Analysis (EDA)

---

#### Outcome

The final result is a professional-grade intelligence tool that:
- Reveals a market average price baseline of **₪3.45M** across **9,905** active listings.
- Identifies supply-demand gaps (e.g., standard apartments making up **67%** of the total inventory).
- Bridges the gap between raw web data and strategic investment decision-making.

🔗 **GitHub Repository:** *https://github.com/jyyu99/Real-Estate-Market-Analysis-Yad2-2026/tree/main*

---

#### What I Learned

- Managing the end-to-end pipeline from "dirty" raw data to a polished, professional BI product.
- Solving data localization and encoding challenges in complex, multi-language datasets.
- Designing dashboards that prioritize user experience (UX) and business logic over raw complexity.
- Translating technical data metrics into clear, visual market stories for stakeholders.