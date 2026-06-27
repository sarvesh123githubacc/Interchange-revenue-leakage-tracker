# Interchange Revenue Leakage Tracker

## Overview

The **Interchange Revenue Leakage Tracker** is an interactive Power BI dashboard designed to identify, monitor, and analyze potential revenue leakage in credit card interchange transactions caused by merchant MCC (Merchant Category Code) mismatches.

The dashboard provides business users with real-time KPIs, merchant-level insights, leakage trends, and category analysis to support operational monitoring and data-driven decision making.

---

## Business Problem

Incorrect Merchant Category Code (MCC) mappings can lead to incorrect interchange fee calculations, resulting in revenue leakage.

This dashboard enables business teams to:

- Detect miscoded merchants
- Monitor leakage trends
- Identify high-impact merchants
- Analyze leakage across merchant categories
- Support operational controls and business health monitoring

---

## Dashboard Features

### Executive KPI Summary

Provides high-level business metrics including:

- Total Transactions
- Miscoded Rate (%)
- Leakage Rate (%)
- Total Leakage Amount
- Total Transaction Amount

---

### Merchant Category Analysis

Analyze leakage across merchant categories such as:

- Travel
- Electronics
- Entertainment
- Retail
- Digital

to identify high-risk business segments.

---

### Merchant-Level Analysis

Visualizes leakage contribution by merchant, enabling users to quickly identify merchants responsible for the highest revenue loss.

---

### Monthly Leakage Trend

Tracks leakage amount across months, helping identify seasonal patterns and operational issues.

---

### High Yield Merchant Analysis

Compare spending between:

- High Yield Merchants
- Low Yield Merchants

to understand their contribution towards interchange revenue.

---

### Miscoded Merchant Detection

Interactive table displaying:

- Merchant Name
- Correct MCC
- Registered MCC
- Miscoded Status

to support operational investigation and data quality improvements.

---

## Key Insights

- Identify merchants responsible for maximum interchange revenue leakage.
- Monitor miscoding rates and their financial impact.
- Analyze merchant categories with the highest leakage.
- Track monthly leakage trends.
- Improve operational controls by detecting incorrect MCC mappings.

---

## Business Value

The dashboard supports business teams by:

- Improving revenue visibility
- Reducing financial leakage
- Supporting operational decision making
- Enabling proactive merchant monitoring
- Strengthening business reporting through interactive KPIs

---

## Tech Stack

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modeling
- Business Intelligence
- Data Visualization

---

## Skills Demonstrated

- Business Intelligence
- KPI Development
- Dashboard Design
- Data Modeling
- DAX Measures
- Power Query
- Financial Data Analysis
- Revenue Leakage Analysis
- Interactive Reporting
- Business Analytics

---

## Project Structure

```
Interchange-Revenue-Leakage-Tracker/
│
├── Dashboard/
│   └── Interchange_Revenue_Leakage_Tracker.pbix
│
├── Data/
│   ├── interchange_data.xlsx
│
├── README.md
```

---

## Dashboard Preview

<img width="1187" height="647" alt="Screenshot 2026-06-27 123350" src="https://github.com/user-attachments/assets/7ae6c97d-c2d7-4608-ba39-5652d7374870" />


---

## Future Enhancements

- Drill-through merchant investigation
- Automated anomaly detection
- Predictive leakage forecasting
- Power BI Service deployment with scheduled refresh
- Executive alerting for high-risk merchants
