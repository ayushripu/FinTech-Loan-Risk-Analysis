# 📊 FinTech Loan Risk Analysis & Power BI Dashboard

## 📌 Project Overview

The **FinTech Loan Risk Analysis Dashboard** is an interactive Power BI project developed to analyze loan performance, collections, repayment behavior, credit risk, and customer loan patterns.

The dashboard transforms raw loan data into meaningful business insights using **Power BI, DAX, Power Query, Excel, and data modeling**.

The main objective of this project is to help financial institutions monitor loan portfolios, identify risky loans, analyze collection performance, and understand repayment trends through an interactive dashboard.

---

## 🎯 Project Objectives

- Analyze overall loan portfolio performance.
- Monitor total loans and total loan amount.
- Analyze monthly loan trends.
- Track monthly loan amount and collection trends.
- Identify high-risk loan categories.
- Analyze loan status distribution.
- Monitor repayment status.
- Analyze DPD (Days Past Due) / delinquency distribution.
- Calculate collection, NPA, and default rates.
- Compare loan performance across different loan types.
- Provide interactive filtering for business analysis.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard development and data visualization |
| **DAX** | Measures and KPI calculations |
| **Power Query** | Data cleaning and transformation |
| **Excel** | Data source and initial data inspection |
| **Data Modeling** | Relationships and analytical structure |

---

## 📂 Dataset

The project uses a FinTech loan dataset containing information related to:

- Customer details
- Loan information
- Repayment information
- Loan risk
- Payment status
- Dates and monthly trends

### Main Dataset Tables

- `Customer`
- `Loan`
- `Repayment`
- `Loan_Risk`
- `Date`
- `Known_Issues`

---

## 🧹 Data Cleaning & Transformation

The dataset was prepared using **Power Query** before creating the dashboard.

Major data preparation steps included:

- Handling missing/null values
- Removing duplicate records
- Correcting inconsistent values
- Standardizing categorical values
- Formatting date columns
- Creating required calculated fields
- Creating relationships between tables
- Creating a dedicated Date table
- Creating calculated columns required for risk analysis

---

## 📐 Data Modeling

A structured data model was created in Power BI to connect customer, loan, repayment, risk, and date information.

The model allows the dashboard to analyze:

```text
Customer
    │
    └── Loan
          │
          ├── Repayment
          │
          └── Loan_Risk

Date ───────────────► Loan / Repayment
