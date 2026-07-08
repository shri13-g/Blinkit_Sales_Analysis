# Blinkit Performance & Sales Analytics Dashboard

[![Power BI](https://img.shields.io/badge/Power_BI-Desktop-F2C811?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-0552B5?logo=microsoft)](https://learn.microsoft.com/en-us/dax/)

## 📌 Executive Summary
This project delivers a comprehensive, end-to-end data analytics solution analyzing **Blinkit's** sales performance, customer preferences, and outlet distributions. By converting raw transactional data into actionable operational insights, this dynamic Power BI dashboard highlights critical revenue drivers, optimizes product placements, and identifies structural growth opportunities across multiple outlet tiers and sizes.

### 📊 Dashboard Preview
<img width="1279" height="744" alt="blinkt report dashboard" src="https://github.com/user-attachments/assets/4c8c6d7e-333e-4cba-a4c2-2c0868318eb4" />


---

## 🛠️ Tech Stack & Architecture
* **Data Visualization:** Power BI Desktop (Dynamic reporting, custom canvas layouts, and cross-filtering)
* **Data Modeling & Analytics:** DAX (Data Analysis Expressions) for complex calculated measures, time-series trends, and conditional formatting KPI states
* **ETL & Data Transformation:** Power Query (Data cleaning, schema enforcement, type casting, and attribute structuralization)

---

## 📈 Key Metrics & High-Level KPIs
The dashboard tracks four primary business health indicators, dynamically driven by specific user filter contexts:
* **Total Revenue ($230.49K):** Aggregate sales across filtered locations and sizes.
* **Average Order Sales ($142):** Average value generated per transactional record.
* **Total Items Sold (1,624 Units):** Total volume moving through the network.
* **Average Rating (3.9 / 5.0):** Aggregated customer satisfaction benchmark.

---

## 🔍 Core Analytical Perspectives (Chart Blueprint)

| Analytical Focus | Business Objective | Visual Implementation |
| :--- | :--- | :--- |
| **Fat Content Analysis** | Assess revenue impact and volume variations between Low Fat vs. Regular consumer groups. | **Donut Chart** with absolute and percentage splits ($141.93 Avg Sales base). |
| **Item Type Breakdown** | Identify high-volume and high-value product categories out of 16 granular departments (Household, Dairy, Snacks, etc.). | **Horizontal Bar Chart** sorted by descending financial yield. |
| **Fat Content by Outlet** | Cross-analyze regional preference structures for inventory alignment across localized outlets. | **Stacked Column Chart** tracking absolute category values. |
| **Outlet Establishment Timeline** | Evaluate the performance lifecycle and historical growth trajectory of physical stores across timeline metrics. | **Line / Area Chart** tracking structural peaks ($133K in 2017 down to $50K floor limits). |
| **Outlet Size Correlation** | Segment market penetration by operational scale (Small, Medium, Large) to optimize real estate utility. | **Donut Chart** evaluating proportional volume contributions. |
| **Geographic Distribution** | Pinpoint regional concentration and market saturation across urban layout classifications. | **Horizontal Funnel Distribution** tracking absolute tier distributions. |
| **Holistic Operational Matrix** | Deliver a unified summary view mapping all core KPIs strictly segmented by store formats. | **Matrix Grid** featuring micro-level color indicator metrics. |

---

## 💡 Strategic Business Insights Formulated
1. **The Small Format Powerhouse:** Small-sized outlets accounted for 100% of the active filtered subset sales ($230.49K), indicating that dense, hyper-local mini-fulfillment hubs drive maximum operational velocity for quick-commerce constraints.
2. **Category Anchors:** *Household* ($151.50 Avg) and *Snack Foods* ($151.18 Avg) top the ticket size rankings, suggesting secondary cross-selling placement strategies should center around these high-ticket anchors.
3. **Establishment Maturation Shifts:** Outlets established in 2017 saw a historic peak of $133K in volume, revealing a stabilization curve or localized competition surge that affected newer installations leading into 2020. 

---

## 🚀 How to Run and Interact with the Dashboard
1. Ensure you have the latest version of **Power BI Desktop** installed.
2. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/Atharw10/blinktsales_analysis.git](https://github.com/Atharw10/blinktsales_analysis.git)
