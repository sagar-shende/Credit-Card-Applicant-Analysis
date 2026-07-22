# 💳 Credit Card Applicant Analysis

[![SQL](https://img.shields.io/badge/SQL-MySQL-blue?logo=mysql)](#)
[![Python](https://img.shields.io/badge/Python-Pandas%20%7C%20NumPy%20%7C%20Seaborn-yellow?logo=python)](#)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)](#)
[![Excel](https://img.shields.io/badge/Excel-Analysis-217346?logo=microsoftexcel)](#)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An end-to-end data analytics project that analyzes credit card applicant data to identify risk patterns, approval trends, and customer segments — built using SQL, Python, Excel, and Power BI.

---

## 📌 Project Overview

Banks and financial institutions receive thousands of credit card applications and must assess applicant risk before approval. This project analyzes applicant demographic and credit history data to uncover patterns in **income, employment, family status, and credit behavior**, helping simulate the kind of risk assessment used in real-world lending decisions.

The project demonstrates a complete analytics workflow: raw data → SQL querying → Python EDA → Excel reporting → interactive Power BI dashboard.

---

## ❓ Business Problem

Credit card issuers need to answer key questions before approving an application:

- Which applicant segments carry higher credit risk?
- Does income, occupation, or family status correlate with repayment behavior?
- How can the approval process be made more data-driven and less subjective?

This project analyzes historical applicant and credit record data to surface insights that support smarter, risk-aware approval decisions.

---

## 🗂️ Dataset

| File | Description |
|------|-------------|
| `application_record.csv` | Applicant demographic details — income, occupation, family status, housing type, etc. |
| `credit_record.csv` | Monthly credit history per applicant — payment status and account age |

> Source: Public credit card approval dataset (Kaggle-style structure).

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **MySQL** | Data cleaning, joins, and exploratory querying |
| **Python** (Pandas, NumPy, Matplotlib, Seaborn) | EDA, feature engineering, visualization |
| **Excel** | Pivot tables, quick analysis, summary reporting |
| **Power BI** (DAX, Power Query) | Interactive dashboard and KPI visualization |

---

## 📊 KPIs (10) – Card Visuals

1. Total Customers
2. Total Annual Income
3. Average Annual Income
4. Average Customer Age (from `DAYS_BIRTH`)
5. Average Employment Duration (from `DAYS_EMPLOYED`)
6. Car Ownership Rate (%)
7. Real Estate Ownership Rate (%)
8. Average Family Size
9. Average Number of Children
10. Customers with Contact Information (%) (Phone/Email/Work Phone)

---

## 🔍 EDA Questions (20) – Charts/Graphs

**Customer Demographics**
1. What is the gender distribution of customers?
2. Which age group has the highest number of customers?
3. Which family status has the highest number of customers?
4. Which housing type has the highest number of customers?

**Income Analysis**
5. Which income type has the highest number of customers?
6. Which income type has the highest average annual income?
7. Which education level has the highest average annual income?
8. Which occupation has the highest average annual income?
9. How does annual income vary across age groups?
10. How does annual income vary by family status?

**Education & Occupation**
11. Which education level is most common among customers?
12. Which occupation has the highest number of customers?
13. What is the relationship between education level and occupation?

**Asset Analysis**
14. Which income type has the highest car ownership?
15. Which education level has the highest real estate ownership?
16. Which occupation has the highest real estate ownership?

**Family Analysis**
17. Which family status has the highest average number of children?
18. Which housing type has the largest average family size?

**Contact Analysis**
19. Which occupation has the highest email usage?
20. Which income type has the highest work phone availability?

---

## 📈 Dashboard Preview

| Page 1 | Page 2 | Page 3 |
|--------|--------|--------|
| ![Dashboard Page 1](Images/dashboard_page1.png) | ![Dashboard Page 2](Images/dashboard_page2.png) | ![Dashboard Page 3](Images/dashboard_page3.png) |

📄 Full dashboard export: [`Dashboard.pdf`](PowerBI/Dashboard.pdf)

---

## 💡 Key Insights

- Applicants with **stable, longer employment history** show noticeably lower overdue/default rates.
- **Income level alone** is a weak predictor of risk — family status and housing type add meaningful signal.
- A small segment of applicants accounts for a disproportionate share of overdue accounts, suggesting targeted risk monitoring over blanket rejection.
- Certain occupation categories consistently show higher approval-worthy profiles.

---

## 📁 Folder Structure

```
Credit-Card-Applicant-Analysis/
│
├── README.md
├── Data/
│   ├── application_record.csv
│   └── credit_record.csv
│
├── Excel/
│   └── Credit_Card_Analysis.xlsx
│
├── SQL/
│   └── credit_card_analysis.sql
│
├── Python/
│   ├── Credit_Card_Analysis.ipynb
│   └── requirements.txt
│
├── PowerBI/
│   ├── Credit_Card_Analysis.pbix
│   └── Dashboard.pdf
│
├── Images/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│   └── dashboard_page3.png
│
└── LICENSE
```

---

## 👤 Author

**Sagar Shende**
Data Analyst | SQL • Python • Power BI • Excel

🔗 GitHub: [github.com/sagar-shende](https://github.com/sagar-shende)

---

⭐ If you found this project useful, consider giving the repo a star!
