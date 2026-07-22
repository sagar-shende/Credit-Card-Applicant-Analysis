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

## 📊 KPIs

- Total Applicants
- Approval Rate (%)
- Average Applicant Income
- Default / Overdue Rate
- Applicant Distribution by Occupation & Family Status
- Income vs. Credit Risk Correlation

---

## 🔍 EDA Questions

1. What is the overall approval vs. rejection distribution?
2. How does income level vary across occupation types?
3. Is there a relationship between family size and credit risk?
4. Which housing type shows the highest concentration of risky applicants?
5. Do applicants with longer employment history show better credit behavior?
6. How does age group correlate with default rate?

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
