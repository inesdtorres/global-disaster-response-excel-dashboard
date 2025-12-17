# global-disaster-response-excel-dashboard

# Global Disaster Response Analysis (2018–2024)

## Overview
This project presents an interactive Excel dashboard analysing global disaster response efficiency and human impact between 2018 and 2024.

The analysis focuses on how average response times evolve alongside human impact (casualties), while providing financial context through economic losses, aid allocation and coverage ratios.

The dashboard is designed to support exploratory analysis by country, disaster type and year.

---

## Dataset
Global disaster response dataset covering the period 2018–2024.

Key fields:
- Year
- Country
- Disaster type
- Response time
- Casualties
- Economic loss (USD)
- Aid amount (USD)

---

## Methodology
- Data preparation and cleaning performed in Excel
- Aggregations built with PivotTables
- Dynamic KPIs calculated using `GETPIVOTDATA`
- Time values handled as day fractions and formatted using `[h]:mm`
- Interactive analysis enabled through slicers and pivot filters
- Dashboard layout designed to fit a single screen without scrolling

---

## Key Metrics
- **Total Economic Loss (USD)**
- **Total Aid Amount (USD)**
- **Aid Coverage Ratio**
- **Number of Events**

---

## Key Insight
Response efficiency and human impact do not always move together, highlighting the importance of contextual risk factors beyond operational speed alone.

---

## Dashboard Features
- KPI cards with dynamic aggregation
- Dual-axis line chart showing:
  - Average response time (hh:mm)
  - Total casualties
- Filters by year, country and disaster type
- Fully interactive, no manual refresh required

---

## Tools
- Microsoft Excel
  - PivotTables
  - GETPIVOTDATA
  - Combo charts
  - Slicers and pivot filters
  - Advanced formatting and layout design

---

## Preview
![Dashboard overview](images/dashboard_overview.png)
