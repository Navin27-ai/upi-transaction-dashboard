# 💳 UPI Transaction Analysis Dashboard

## ℹ️ Introduction
The **UPI Transaction Analysis** project transforms high-volume payment transaction data into **actionable business insights** across 2 primary executive views: **Transaction Overview** and **Operational Overview**. Standardized across a structured grid layout with cohesive **Forest Green (#062C19)** branding[cite: 5], the dashboard analyzes total payment volume (TPV), transaction success rates, bank reliability, fraud density, demographic device usage, and value tier distributions[cite: 5, 8].

## 🛠️ Skill Showcase

| Tech Stack | Core Skills Demonstrated | Practical Application |
| :--- | :--- | :--- |
| **Power BI & DAX** | Time Intelligence, DAX Calculations, Custom UI/UX | Built a **2-page executive dashboard** with custom calculated columns (`Amount Bucket`) and dynamic KPI cards[cite: 5, 8]. |
| **Data Modeling** | Star Schema & Relationship Design | Modeled `fact_upi_transactions` connected to `Dim_Calendar` and `Dim_Bank`[cite: 8]. |
| **Fintech Analytics** | Payment Volume & Risk Analytics | Evaluated TPV, transaction velocity, fraud counts, bank success rates, and user demographic distributions[cite: 5, 8]. |

---

## 📊 Dashboard Overview

### 1. Transaction Overview Page
![Transaction Overview](/Transaction%20Overview.png)

### 2. Operational Overview Page
![Operational Overview](/Operational%20Overview.png)

---

## 💡 Key Business Insights & Recommendations

Based on the analysis of the transaction dataset, the dashboard reveals several critical operational and commercial patterns:

### 1. Payment Volume & Network Performance
* **Dominant Payment Tiers:** **Micro (< ₹500)** transactions account for the largest share of total transaction count[cite: 5], while **High Value (> ₹10K)** transactions drive overall Payment Volume[cite: 5].
* **Bank Reliability:** Leading banking partners like **SBI, HDFC, and ICICI** drive the bulk of settlement volume[cite: 8], with high success rates maintaining network stability[cite: 5].

### 2. Demographic & Hourly Risk Dynamics
* **User Demographics:** The **26–35 age group** represents the highest payment volume, with **Android** dominating platform usage across all age brackets[cite: 9].
* **Peak Hourly Activity & Fraud:** Transaction volume peaks during evening hours, corresponding with a slight rise in risk density and failed attempts[cite: 10].

---

### 🎯 Strategic Business Recommendations
1. **Optimize Peak Hour Capacity:** Partner with top-tier banks to enhance server handling during peak hourly transaction spikes to reduce failure rates[cite: 10].
2. **Target Micro-Transaction Infrastructure:** Streamline processing pipelines for Micro (< ₹500) transactions to handle high-frequency low-value volume smoothly[cite: 5].
3. **Enhance Android App Experience:** Prioritize mobile app performance and security optimizations on Android due to its dominant share across all age demographics[cite: 9].
