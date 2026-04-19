# 📉 Customer Churn Analysis Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Built%20with-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Dataset](https://img.shields.io/badge/Dataset-Telco%20Churn%20(Kaggle)-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

![Executive Summary](screenshots/summary.png)

## 📌 Project Overview

This Power BI dashboard provides an end-to-end visual analysis of customer churn behavior for a telecommunications company. Built using the popular **Telco Customer Churn dataset from Kaggle**, the dashboard helps stakeholders understand *who* is churning, *why* they are churning, and *what revenue impact* churn is causing — enabling data-driven retention strategies.

---

## 📂 Data Source

| Field | Details |
|---|---|
| **Dataset** | Telco Customer Churn (Kaggle) |
| **Records** | 7,043 customers |
| **Format** | CSV |

### Key Fields Used

- `customerID` — Unique customer identifier
- `gender`, `SeniorCitizen`, `Partner`, `Dependents` — Demographic attributes
- `tenure` — Number of months the customer has been with the company
- `Contract` — Contract type (Month-to-month, One year, Two year)
- `MonthlyCharges`, `TotalCharges` — Billing information
- `InternetService`, `TechSupport`, `StreamingTV` — Service subscriptions
- `Churn` — Target variable (Yes / No)

---

## 📊 Key KPIs & Metrics

| KPI | Description |
|---|---|
| **Churn Rate %** | Percentage of customers who churned out of total customers |
| **Total Churned Customers** | Absolute count of customers who left |
| **Revenue Lost** | Total charges attributed to churned customers |
| **Churn by Demographics** | Breakdown by gender, senior citizen status, partner, and dependents |
| **Churn by Contract Type** | Churn rate segmented by month-to-month, one-year, and two-year contracts |
| **Churn by Tenure** | Churn distribution across customer tenure bands |

---

## 💡 Key Insights

1. **Significant Churn Impact on Revenue:** The company faces a **27.0% overall churn rate**, translating to **$1.06 Million in Total Revenue at Risk** out of $5.99 Million in total revenue — over one-sixth of total revenue.

2. **Month-to-Month Contracts are a Major Vulnerability:** 50.95% of all customers are on Month-to-Month contracts, which exhibit the highest churn rates. Customers with less than 1 year of tenure on these contracts show a peak churn rate of **46.7%**, indicating a critical risk for new and short-term customers.

3. **Fibre Optic Customers are Disproportionately Churning:** Fibre Optic users account for **66.79% of all churned customers** and contribute **62.53% of Monthly Charges at Risk**, meaning the highest-value internet customers are leaving at an alarming rate.

4. **Regional Churn Hotspots Demand Urgent Attention:** **Jammu & Kashmir (54.0%)** and **Chhattisgarh (40.9%)** exhibit churn rates far above the 27.0% overall average, indicating region-specific issues requiring immediate focus.

5. **Competitors and Dissatisfaction are the Primary Churn Drivers:** A combined **~60% of churn** is attributed to external competition (42.69%) and internal customer dissatisfaction (17.27%), suggesting customers are finding better alternatives or are unhappy with service quality and pricing.

6. **Low Adoption of Value-Added Services Correlates with Higher Churn:** Services like Online Security, Streaming TV, Streaming Music, and Streaming Movies have low adoption rates. For most of these services, churned customers without the service outnumber or match those with it — implying that low ecosystem engagement may increase churn propensity.

7. **Long-Term Contracts Significantly Reduce Churn Risk:** Customers on **Two-Year contracts have the lowest churn rate (2.47%)** and contribute **40% of total revenue**, strongly suggesting that securing long-term commitments is a highly effective retention and revenue stability strategy.

---

## ✅ Recommendations

1. **Targeted Retention Program for Fibre Optic Customers:** Conduct surveys, exit interviews, and service quality audits specifically for Fibre Optic customers — especially in high-churn regions — to understand and address the precise reasons for departure.

2. **Enhanced Onboarding for New & Month-to-Month Customers:** Introduce a proactive **30/60/90-day onboarding program** for new customers with personalized outreach, value reinforcement, and early issue resolution. Offer conversion incentives to longer-term contracts after a positive initial experience.

3. **Region-Specific Churn Mitigation Initiatives:** Assign dedicated resources to investigate the root causes of high churn in **Jammu & Kashmir** and **Chhattisgarh**, covering competitive landscape assessment, network infrastructure audits, and local customer support improvements.

4. **Strengthen Competitive Positioning:** Counter the 42.69% competitor-driven churn through competitive pricing reviews, value-added bundles, and superior customer service to reduce the appeal of switching.

5. **Drive Adoption of Value-Added Services:** Design targeted marketing campaigns and attractive service bundles — especially around Online Security and Streaming services — to deepen customer engagement and reduce churn propensity among basic-plan subscribers.

---

## 🖼️ Dashboard Pages

<details>
<summary>📂 Click to explore all dashboard pages</summary>

### Customer Risk Assessment
> Breaks down churn by internet type, tenure, contract, and churn reasons with revenue at risk metrics.

![Customer Risk](screenshots/customer_risk.png)

### Services Offered
> Shows churn distribution across all services — Phone, Internet, Streaming, Security, and more.

![Services Offered](screenshots/services.png)

### Finances
> Revenue breakdown by contract type, payment method, state, value deals, and charge type.

![Finances](screenshots/finances.png)

</details>

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** — Dashboard design, DAX measures, and data modeling
- **Power Query** — Data cleaning and transformation
- **DAX** — Custom KPI calculations (churn rate, revenue lost, etc.)

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open the `.pbix` file in **Power BI Desktop** (free download from [Microsoft](https://powerbi.microsoft.com/desktop/)).
3. If prompted, refresh the data source and point it to the included CSV file.
4. Explore the dashboard pages using the navigation tabs at the bottom.

---

## 📁 Repository Structure

```
📦 churn-dashboard
 ┣ 📊 Churn_Dashboard.pbix                      # Power BI dashboard file
 ┣ 📄 WA_Fn-UseC_-Telco-Customer-Churn.csv      # Source dataset
 ┣ 📁 screenshots/
 ┃ ┣ 🖼️ summary.png                             # Executive Summary page
 ┃ ┣ 🖼️ customer_risk.png                       # Customer Risk page
 ┃ ┣ 🖼️ services.png                            # Services Offered page
 ┃ ┗ 🖼️ finances.png                            # Finances page
 ┗ 📝 README.md                                 # Project documentation
```

---

## 🙋‍♂️ Author

Feel free to connect or reach out if you have feedback or questions!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/mohd-saad-choudhary-b8675428b/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/Saad01042005)
