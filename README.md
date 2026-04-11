# Fuel Sales & Logistics Performance Dashboard

An interactive Excel dashboard analyzing both **fuel sales performance** and **logistics operations** across regions and fuel stations.

---

## 📊 Dashboard Preview

### Sales Dashboard

![Sales Dashboard](Sales_dashboard.png)

### Logistics Dashboard

![Logistics Dashboard](Logistics_dashboard.png)

---


# Fuel Sales & Logistics Performance Dashboard

An Excel dashboard analyzing fuel sales performance and logistics operations across regions and stations, built to answer real operational questions about revenue, delivery efficiency, and demand patterns.

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/Pivot_Tables_%26_Charts-217346?style=flat)
![Slicers](https://img.shields.io/badge/Slicers-217346?style=flat)

---

## 🎯 Business Problem

Fuel distributors operating across multiple regions and stations face a recurring challenge: revenue and delivery data exist in separate operational reports, making it difficult to answer critical questions all at once:

- Which fuel types and regions are driving the most revenue?
- Are high-revenue regions also the most efficient to serve logistically?
- Which stations are underperforming relative to their delivery volume?
- Where are delivery costs disproportionately high compared to revenue generated?

This project consolidates sales and logistics data into two interactive dashboards so stakeholders can answer these questions without switching between spreadsheets.

---

## 📊 Key Performance Indicators

| Metric | Value |
|---|---|
| Total Revenue | GHS 3,875,218.60 |
| Total Profit | GHS 658,353.60 |
| Total Liters Sold | 3,291,768 L |
| Profit Margin | 16.99% |
| Total Delivery Volume | 3,291,768 L |
| Total Delivery Cost | GHS 164,588.40 |
| Delivery Efficiency | 4.30% |

---

## 🔧 My Process

**1 — Data cleaning & structuring**
Standardized date formats, verified fuel type categories, checked for missing delivery records, and validated that revenue and cost figures were consistent across all 15 stations and 5 regions.

**2 — Separating sales and logistics concerns**
Decided early to split the analysis into two dashboards rather than one, because sales metrics (revenue, profit, margin) and logistics metrics (delivery volume, cost, efficiency) serve different audiences and decision types.

**3 — Pivot table design**
Built pivot tables for monthly revenue by fuel type, regional revenue comparison, top-performing stations, delivery volume by region, delivery cost by fuel type, and delivery efficiency ratio (cost ÷ revenue).

**4 — Slicer logic**
Connected Region, Fuel Type, and Station slicers across both dashboards so filters applied in one view reflect across all charts simultaneously, enabling cross-functional analysis without manual filtering.

**5 — KPI card design**
Chose to surface 7 KPIs prominently at the top of each dashboard — the numbers a manager would ask for in the first 30 seconds of a briefing.

---

## 🔍 Key Findings & Business Implications

### Sales Dashboard

- **Petrol dominates at 51% of revenue, diesel at 37%** — two fuel types drive 88% of all revenue. LPG, while lowest in volume, should be monitored for margin contribution before any decisions on inventory reduction are made.

- **Central region leads in revenue**, but this concentration creates risk — a supply disruption or demand shift in Central would have outsized impact on overall performance.

- **Station 1 and Station 11 are the top two performers.** The performance gap between the top 5 and lower-ranking stations is significant, suggesting an opportunity to identify what drives Station 1's results and replicate those conditions elsewhere.

- **Diesel shows stable monthly demand; Petrol and LPG show seasonal fluctuation.** This has direct implications for procurement: diesel can be ordered at a steady cadence, while petrol purchasing should account for peak periods.

### Logistics Dashboard

- **Delivery efficiency of 4.3%** means logistics cost consumes less than 5 cents of every GHS 1 of revenue — a healthy ratio. Worth tracking per-litre as volumes scale.

- **Eastern and Greater Accra have the highest delivery volumes, yet Central leads in revenue.** This mismatch warrants further investigation — are Eastern/Greater Accra stations operating on lower margins?

- **Monthly delivery peaks around mid-year** suggest seasonal demand. Aligning logistics capacity planning to this pattern could reduce operational strain during peak months.

---

## 📋 Dashboard Features

| Dashboard | Chart / View | Business Question Answered |
|---|---|---|
| Sales | Monthly fuel revenue trend | When are our peak revenue months? |
| Sales | Revenue by fuel type (pie) | Which fuel drives our business? |
| Sales | Regional revenue comparison | Where are our strongest markets? |
| Sales | Top 5 performing stations | Which stations should we learn from? |
| Logistics | Monthly delivery volume trend | Are deliveries aligned with demand cycles? |
| Logistics | Delivery volume by region | Where do we move the most fuel? |
| Logistics | Delivery cost by fuel type | Which fuel type is most expensive to move? |
| Logistics | Top 5 stations by delivery volume | Which stations drive our logistics load? |
| Logistics | Delivery efficiency ratio | How lean is our logistics operation? |

---

## 🛠 Tools & Techniques

| Tool / Technique | How It Was Used |
|---|---|
| Microsoft Excel | Primary analysis and dashboard environment |
| Pivot Tables | Aggregating revenue, volume, and cost by region, fuel type, station, and month |
| Pivot Charts | Line charts for trends, bar charts for comparisons, pie chart for fuel type share |
| Slicers | Interactive filtering by Region, Fuel Type, and Station across both dashboards |
| KPI Cards | Summary metrics surfaced as high-visibility cards for executive-level readability |
| Calculated Fields | Profit margin (profit ÷ revenue) and delivery efficiency (delivery cost ÷ revenue) |

---

## 📁 Files Included

| File | Description |
|---|---|
| `fuel_sales_logistics_dashboard.xlsx` | Interactive Excel dashboard with slicers — full functionality |
| `fuel_sales_logistics_dashboard.pdf` | Static export for quick preview without Excel |
| `fuel_sales_logistics_dataset.csv` | Raw dataset used for analysis |
| `Sales_dashboard.png` | Screenshot of sales dashboard view |
| `Logistics_dashboard.png` | Screenshot of logistics dashboard view |

---

## 💼 Transferable Skills Demonstrated

- Translating operational data into business-ready insights — applicable across supply chain, retail, energy, and FMCG sectors
- Structuring analysis around distinct stakeholder needs (sales team vs. logistics team)
- Designing interactive dashboards that allow non-technical users to explore data independently
- Identifying operational inefficiencies and revenue patterns from raw transactional data
- Communicating findings with clear business context, not just numbers

---

*Dataset is simulated to reflect real-world fuel distribution operations.*
