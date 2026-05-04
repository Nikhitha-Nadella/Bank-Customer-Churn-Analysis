# 🏦 Bank Customer Churn Risk Analysis

A full-cycle Power BI analytics project focused on diagnosing the root causes of customer attrition in the banking sector and generating actionable retention intelligence.

---

## 📌 Project Objective

To identify *who* is churning, *why* they're churning, and *what it costs* the business — using segmentation, financial KPIs, and behavioural analysis to support the retention strategy team.

**Key business questions:**
- Which customer segments have the highest churn risk?
- What is the financial impact (balance lost) of churned customers?
- Do geography, age, or product count drive attrition?
- How do churned customers differ behaviourally from retained ones?

---

## 🛠️ Tools & Skills Used

| Tool | Purpose |
|---|---|
| Power BI | Dashboard design, navigation, interactive visuals |
| DAX | Complex measures, calculated columns, segment binning |
| Data Modelling | Relationship design across customer attributes |
| Box Plot Visual | Statistical comparison of balance distributions |

---

## 📊 Dashboard Architecture

The report follows a strict 3-page hierarchy for progressive analysis:

**Page 1 — Executive Summary**
- High-level KPIs: total customers, churn rate, total balance lost, average balance lost
- Funnel overview of churn by key dimensions

**Page 2 — Demographic & Geographic Risk**
- Churn rate by geography, age group, gender, and credit score band
- Segment churn rate (DAX measure) — true proportional risk, not raw counts

**Page 3 — Behavioural & Financial Deep Dive**
- Box plot comparing balance distribution: churned vs retained customers
- Revenue impact: total and average balance lost per segment
- Product count analysis and its relationship to churn likelihood

---

## 🧠 Key DAX Measures Built

- `Segment Churn Rate` — calculates true proportional risk per group, avoiding misleading raw count comparisons
- `Total Balance Lost` — revenue impact of churned customers
- `Average Balance Lost` vs `Average Balance Retained` — comparative financial KPIs
- Age Group and Credit Score bins via DAX Calculated Columns

---

## 💡 Key Findings

- Churned customers hold significantly higher account balances — making this a high-value retention problem
- Geography and age band are the strongest predictors of churn risk
- Customers with only 1 product churn at a disproportionately high rate
- Android and organic users show stronger retention in digital channels

---

## 📂 Repository Contents

```
Bank-Customer-Churn-Analysis/
│
├── Churn_Modelling.csv              # Source dataset
├── Customer Churn Analysis.pbix    # Power BI report file
├── executive summary.jpg           # Dashboard screenshot - Page 1
├── Demo Graphic and Geographic risk.jpg  # Dashboard screenshot - Page 2
├── Behavioural and financial deep dive.jpg  # Dashboard screenshot - Page 3
└── README.md
```

---

## 👩‍💻 About Me

**Nikhitha Nadella** — Data Analyst with 3+ years of experience in banking and financial services.

🔗 [LinkedIn](https://www.linkedin.com/in/nikhithanadella/) | [GitHub](https://github.com/Nikhitha-Nadella) | nikkinadella@gmail.com
