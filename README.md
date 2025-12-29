# 🛡️ Insurance Operations & Financial Monitoring Dashboard

## 📌 Project Overview
This project delivers a real-time operational monitoring suite for an insurance provider managing a portfolio of **800 policyholders**. The dashboard highlights a critical **"Red Zone" financial status**, where total claims paid significantly outweigh current gross premiums. This framework is designed to facilitate emergency underwriting reviews and strategic capital reallocation.

---

## 📊 Live Interactive Dashboard
Experience the full interactivity of the reporting suite:
**[👉 View Live Insurance Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMTkwNDY3NzYtMmNhZC00OThkLWFiMDktYjE1ZTAyZGYzMjRmIiwidCI6IjE0MDc0NzdmLTI1YTQtNDkzMi1hMDY4LTBlMzk0OGFjYTJiOCJ9)**

---

## 📷 Dashboard Preview
![Insurance Dashboard Overview](Dashboard)

---

## 💡 Key Insights: The "Red Zone" Analysis
* **Critical Deficit**: The company is currently operating in a deep deficit. While **Gross Premium** stands at **$3.92M**, the **Total Claims Paid** have reached a staggering **$24.86M**.
* **Unbalanced Portfolio**: For every **$1.00** collected in premium, the company has paid out approximately **$6.34** in claims. This indicates a high-risk pool of policyholders and unsustainable underwriting.
* **Liability Bottleneck**: **19.98% (58K)** of claims are still **Pending**. This represents an additional looming liability that could push the deficit even further if not mitigated through strict auditing.

---

## 🎯 Strategic Recommendations & Mitigation
1. **Aggressive Revenue Shift**: The initial target of **$10M** is no longer sufficient to cover existing liabilities. Management must pivot to a **Premium Target of $30M+** to create a sustainable capital buffer above the $24.86M claims mark.
2. **Underwriting Quality Overhaul**: To bridge the **$20.94M gap** between premiums and claims, the company must stop acquiring high-risk "Auto" policies (the lowest revenue driver) and focus exclusively on high-premium **Health** and **Home** segments.
3. **Claim Mitigation**: Immediately audit the **58K pending claims**. Tightening the "Rejected" criteria (currently 21.61%) for non-compliant claims is essential to preserve remaining capital.
4. **Premium Upselling**: Implement a mandatory premium rate review for existing policyholders in Nashville and Indianapolis (top cities) to align their contributions with the actual risk costs seen in the 2024–2025 payout spike.

---

## 🔄 BI Automation & Workflow
* **Data Sourcing**: Connected to **Google Drive** via **Web Connector** for seamless cloud data integration.
* **ETL Engine**: Utilized **Power Query** for advanced cleaning, specifically handling claim status normalization and year-over-year payment trends.
* **Threshold Alerting**: Automated **Microsoft Teams** notifications are triggered when:
    * **Premium Milestone**: The company reaches the interim **$10M recovery target**.
    * **Liability Alert**: Total Claims Paid cross the **$25M threshold**.

---

## 🛠️ Technical Stack
* **Power BI**: Star Schema data modeling and advanced DAX for "Red Zone" financial ratios.
* **Power Query**: Cloud-based ETL and data transformation.
* **Google Drive**: Centralized cloud storage for raw datasets.

---
*Project Completed by Chelagat as part of a Data Analytics Portfolio.*
