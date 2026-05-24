# Logistics Operations Analytics Dashboard

### A comprehensive Power BI analytics solution for logistics and supply chain performance

![Overview Dashboard](https://raw.githubusercontent.com/osondubc-star/logistics-operations-analytics-dashboard/main/OVERVIEW_DASHBOARD.png)

---

## Project Overview

This project is a multi-page Power BI dashboard built to analyze the financial, operational, fleet, and customer performance of a logistics and supply chain company. The goal was to go beyond visualizing numbers — to uncover the business story behind the data and provide actionable recommendations that support data-driven decision-making.
This project was completed as a capstone project for the **TS Academy Data Analytics Program**.

---

## Business Objectives

- Analyze overall revenue performance and profitability
- Evaluate delivery efficiency and identify areas for operational improvement
- Assess fleet utilization and vehicle availability
- Understand customer behavior and revenue concentration
- Identify operational risks hidden within the data

---

## Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard design, data modeling, and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Calculated measures and KPIs |

---

##  Dashboard Pages

### 1. Logistics Operations Overview
![Executive Dashboard](https://raw.githubusercontent.com/osondubc-star/logistics-operations-analytics-dashboard/main/EXECUTIVE_DASHBOARD.png)

A high-level executive summary of the company's overall logistics performance, covering revenue, delivery efficiency, customer base, and incident tracking.
**Key KPIs:** Revenue · Net Profit · Total Deliveries · On-Time Delivery Rate · Total Incidents

---

### 2. Financial & Operational Dashboard
![Financial Dashboard](https://raw.githubusercontent.com/osondubc-star/logistics-operations-analytics-dashboard/main/FINANCIAL_DASHBOARD.png)

A deep dive into the company's revenue streams, operational costs, fuel expenditure by state, maintenance costs by vehicle type, and monthly profit trends.
**Key KPIs:** Revenue · Operational Cost · Total Fuel Cost · Net Profit · Profit Margin

---

### 3. Fleet & Driver Performance Dashboard
![Fleet Dashboard](https://raw.githubusercontent.com/osondubc-star/logistics-operations-analytics-dashboard/main/FLEET_DASHBOARD.png)

Analysis of driver productivity, fleet utilization, truck status, and incident frequency across all drivers and vehicles.
**Key KPIs:** Total Drivers · Active Trucks · Avg Trips Per Driver · Fleet Utilization Rate · Driver Efficiency Rate

---

### 4. Customer & Delivery Dashboard
![Customer Dashboard](https://raw.githubusercontent.com/osondubc-star/logistics-operations-analytics-dashboard/main/CUSTOMER_DASHBOARD.png)

Insight into customer revenue contribution, delivery reliability by state, detention time patterns, and customer type breakdown.
**Key KPIs:** Total Customers · Total Load Volume · Avg Revenue Per Customer · Avg Detention Time · Late Delivery Rate

---

## 🔍 Key Findings & Recommendations

| # | Finding | Recommendation |
|---|---------|---------------|
| 1 | The business generated **$298.62M in revenue** with a **66% profit margin** — for every $100 earned, $66 was kept as profit | Maintain strict cost controls to protect this healthy margin |
| 2 | Only **56% of deliveries** were completed on time — meaning almost half of customers experienced delays | Invest in better route planning and driver scheduling systems |
| 3 | Out of 120 trucks, only **92 were actively running** — 13 inactive, 15 in maintenance (over 20% not generating revenue) | Implement a structured preventive maintenance schedule to reduce downtime |
| 4 | **Fuel costs** were the single largest operational expense | Adopt route optimization tools and fuel monitoring systems to reduce consumption |
| 5 | A **small number of customers** were responsible for the majority of total revenue | Prioritize customer diversification to reduce revenue concentration risk |

---

##  Critical Business Insight: The Unassigned Driver Anomaly

During the analysis, a significant data anomaly was discovered:

> **1,714 trips generating approximately $5.99M in revenue had no Driver ID assigned.**

Trucks, trailers, dates, and distances were all recorded — but the driver field was completely empty.

This is not just a data quality issue. It raises serious business concerns:

- **Accident liability** — If an incident occurs on an unassigned trip, who is held responsible?
- **Payment accountability** — How are drivers compensated for trips they are not linked to?
- **Fraud risk** — Untracked trips create opportunities for revenue manipulation
- **Legal & compliance exposure** — Regulatory requirements typically mandate driver identification for commercial vehicle operations

**Recommendation:** Implement mandatory driver ID assignment at the point of trip creation, and conduct an immediate audit of all unassigned historical trips.

---

## Repository Contents

| File | Description |
|------|-------------|
| `PROJECT.pbix` | Power BI project file — open with Power BI Desktop |
| `EXECUTIVE_DASHBOARD.png` | Executive overview dashboard screenshot |
| `OVERVIEW_DASHBOARD.png` | Logistics operations overview screenshot |
| `FINANCIAL_DASHBOARD.png` | Financial & operational dashboard screenshot |
| `FLEET_DASHBOARD.png` | Fleet & driver performance dashboard screenshot |
| `CUSTOMER_DASHBOARD.png` | Customer & delivery dashboard screenshot |

---

🔗 [LinkedIn](https://www.linkedin.com/in/blessing-osondu)  
[GitHub](https://github.com/osondubc-star)

