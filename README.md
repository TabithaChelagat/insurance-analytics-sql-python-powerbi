# 🛡️ Insurance Analysis: Profitability, Risk, and BI Automation

## 📌 Project Overview
This project provides an end-to-end analytical solution for an insurance provider. It spans the entire data lifecycle: extracting insights using **SQL**, building predictive risk models with **Python**, and deploying a live, automated executive dashboard in **Power BI**. 

---

## 📊 Live Interactive Dashboard
Experience the live dashboard with full interactivity:
**[👉 View Live Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiMTUxNzdhOTgtODI5Ni00MzVmLWFmN2MtZjBmZTA0ZjE2YTFhIiwidCI6IjE0MDc0NzdmLTI1YTQtNDkzMi1hMDY4LTBlMzk0OGFjYTJiOCJ9)**

---

## 📷 Dashboard Preview
![Insurance Dashboard Screenshot](Dashboard)

---

## 🧠 Business Questions Answered
1. **Revenue Performance**: What is our current financial standing regarding Total Premiums Paid versus Gross Premium?
2. **Profitability Analysis**: Which insurance products (Life, Health, Home, Auto) generate the highest profit margins?
3. **Claims Management**: What is the volume and financial impact of "Pending" claims?
4. **Risk Prediction (Python)**: Can we predict which policyholders are likely to default based on their financial profiles?
5. **Channel Efficiency**: Which payment methods are most preferred by high-value customers?

---

## 💡 Key Insights
* **Revenue Milestone**: Successfully tracked **$28.2M in Total Premiums Paid** against a **Gross Premium of $4.7M**.
* **Profitability Leader**: **Life Insurance** is the top-performing segment, contributing **$2.0M (41.6%)** to total profit.
* **Pending Liability**: Identified **218 pending claims**, representing a potential liability of **$2.2M**.
* **Preferred Payments**: **Credit Cards** dominate the transaction landscape at **38.7%**, indicating a high adoption of digital payments.

---

## 🔄 BI Automation & Stakeholder Management
This project goes beyond static visuals by implementing a full BI automation lifecycle:
* **Daily Data Refresh**: Configured Power BI Service to perform an automated data refresh daily at **6:00 PM**.
* **Automated Reporting**: Weekly executive summary reports are automatically emailed to stakeholders every **Monday at 9:00 PM**.
* **Real-Time Alerting**: Integrated Power Automate to trigger **Microsoft Teams notifications** when:
    * Total Premiums Paid reaches **$30M**.
    * Gross Premium exceeds **$5M**.

---

## 🛠️ Technical Stack
* **SQL**: Data cleaning, orphaned record detection, and complex aggregations (CTEs, Window Functions).
* **Python**: Exploratory Data Analysis (EDA) and a calibrated Logistic Regression model for default prediction.
* **Power BI**: DAX measures, data modeling (Star Schema), and Service-level automation.

---
*Project Completed by Tabitha Chelagat as part of a Data Analytics Portfolio.*
