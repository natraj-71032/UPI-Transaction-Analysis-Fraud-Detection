# 💳 UPI Payment Intelligence & Fraud Risk Analysis

![SQL](https://img.shields.io/badge/SQL-Database_Design-blue?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-EDA_%26_Stats-3776AB?style=flat-square&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-Dashboards-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-Data_Validation-217346?style=flat-square&logo=microsoft-excel&logoColor=white)

An end-to-end analytics solution built across **7 UPI datasets (10,000+ transactions)** using **Excel, SQL, Python, Statistics, and Power BI**. This project identifies key fraud risk drivers, reduces operational inefficiencies, and delivers actionable business recommendations to strengthen fraud monitoring and minimize transaction risk.

---

## 📌 Project Overview

This project analyzes UPI transaction data to uncover fraud patterns, customer behavior, merchant risks, transaction failures, and operational performance. By combining relational database modeling, statistical hypothesis testing, and interactive BI dashboards, the pipeline transforms raw transactional data into executive-ready business intelligence.

### 🎯 Business Problem
With the rapid growth of digital payments, UPI platforms face critical operational and security challenges:
- **Fraud Detection & Prevention:** Identifying anomalous patterns before losses scale.
- **Transaction Failures:** Reducing drop-offs caused by technical or user errors.
- **Merchant Risk Management:** Isolating high-risk merchant clusters.
- **Device Security Vulnerabilities:** Mitigating risks from compromised hardware.
- **Customer Experience & Trust:** Maintaining seamless, secure payment flows.

---

## 🗂️ Dataset Overview

The solution integrates **7 relational datasets** representing the full UPI payment ecosystem:

| # | Dataset | Scale / Record Count |
|---|---|---|
| 1 | **Customer Master** | 10,000 Customers |
| 2 | **Device Information** | 12,000 Devices |
| 3 | **UPI Account Details** | 12,000 UPI Accounts |
| 4 | **Merchant Information** | 500 Merchants |
| 5 | **UPI Transaction History** | 10,000 Transactions |
| 6 | **Customer Feedback Surveys** | 4,000 Feedback Records |
| 7 | **Fraud Alert History** | 2,000 Fraud Alerts |

---

## 🛠️ Tech Stack & Tools

| Tool | Role in Pipeline |
|---|---|
| **Excel** | Data validation, quality checks, missing value analysis, foreign key verification, initial cleaning |
| **SQL** | Relational database design (DDL), table creation with constraints, data ingestion, joins & aggregations |
| **Python** | Data cleaning, transformation, feature engineering, EDA, fraud pattern analysis, visualizations |
| **Statistics** | Hypothesis testing — T-Test, ANOVA, Chi-Square Test, and Correlation Analysis |
| **Power BI** | Executive & Fraud Monitoring dashboards, KPI tracking, and interactive filtering |

---

## 📊 Key KPIs Tracked

- **Volume & Value:** Total Transaction Volume, Average Transaction Amount
- **Risk Metrics:** Fraud Rate, Merchant Fraud Ratio, Device Fraud Ratio, Device Risk Analysis
- **Operational Health:** Transaction Failure Rate
- **Engagement:** Customer Activity, Merchant Activity

---

## 🔄 Analytics Workflow

1. **Business Understanding** — Defined analytical goals and KPIs aligned with fraud detection and operational performance.
2. **Data Validation (Excel)** — Verified integrity across customer, merchant, device, account, and transaction relationships.
3. **Database Design (SQL)** — Built a normalized relational schema with constraints and ingested all 7 datasets.
4. **Data Analysis (Python)** — Conducted cleaning, feature engineering, trend analysis, and risk segmentation.
5. **Statistical Validation** — Tested business hypotheses using:
   - *T-Test* for transaction amount comparisons
   - *ANOVA* for merchant-level fraud variance
   - *Chi-Square Tests* for categorical fraud associations
   - *Correlation Analysis* between risk scores and fraud occurrence
6. **Dashboarding (Power BI)** — Built interactive dashboards filterable by **Device Type, Merchant, Region, Time Period, and Transaction Status**.

---

## 💡 Major Insights

### 1. Device Security Risk
- **Feature phones and Android devices** showed higher fraud activity.
- **Rooted devices** were associated with significantly higher fraudulent transaction rates.

### 2. Seasonal Fraud Trends
- Fraud incidents peaked during **June–August**, with **July** recording the highest monthly fraud volume.

### 3. Transaction Failure Analysis
- Overall transaction failure rate stood at **~5.87%**.
- Primary failure drivers were **network issues** and **incorrect PIN entries**.

### 4. Transaction Behavior
- **Send** transactions accounted for **~35%** of total volume; **Receive** transactions accounted for **~34%**.
- **Peer-to-peer (P2P)** and **merchant payments** represented the primary fraud exposure areas.

### 5. Merchant Risk Concentration
- A small subset of merchants accounted for a disproportionately high share of total fraud activity, revealing clear high-risk clusters for targeted monitoring.

---

## 🚀 Business Recommendations & Expected Impact

| Focus Area | Recommended Action | Expected Impact |
|---|---|---|
| **Device Security** | Restrict rooted/jailbroken devices and implement device risk scoring. | **15–25% reduction** in fraudulent transactions |
| **Merchant Monitoring** | Introduce merchant risk scoring and tighten onboarding/KYC validation. | **20%+ reduction** in merchant-related fraud exposure |
| **Failure Handling** | Optimize payment gateway retries and improve network timeout management. | Reduce failure rate from **~5.8% to < 3%** |
| **Peak Season Defense** | Deploy real-time fraud detection and heightened monitoring during June–August spikes. | Faster containment during seasonal surges |
| **Customer Awareness** | Launch scam-prevention and safe UPI usage campaigns. | Higher customer trust & platform adoption |

---

## 📈 Dashboard Features

### Executive Dashboard
- High-level KPIs: Total Transactions, Fraud Rate, Failure Rate, Average Transaction Value
- Device-wise & Merchant-wise performance breakdowns
- Monthly transaction and risk trends

### Fraud Risk Dashboard
- Fraud alert volume trends over time
- High-risk device and merchant identification
- Fraud distribution analysis & root-cause investigation

---

## 🏆 Project Outcome

This project demonstrates how an end-to-end data analytics pipeline—spanning **Excel, SQL, Python, Statistics, and Power BI**—can directly strengthen fraud detection, improve operational reliability, and build customer trust in modern digital payment ecosystems.
