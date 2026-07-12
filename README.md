
# Loan Portfolio Intelligence System

An end-to-end Business Intelligence and Credit Risk Analytics solution built using **Python, SQL, Tableau, and Machine Learning** to analyze lending portfolio performance, monitor portfolio health, and generate actionable business insights.

---

## Project Overview

Financial institutions rely on data-driven portfolio monitoring to minimize credit risk and optimize lending decisions. This project analyzes over **225,000 LendingClub loan records** to understand borrower behavior, portfolio quality, default trends, and credit risk.

The solution includes data preprocessing, exploratory data analysis, predictive modeling, and an executive Tableau dashboard for business intelligence.

---

## Objectives

- Analyze loan portfolio performance
- Identify borrower and portfolio risk patterns
- Predict loan default probability
- Build executive-level BI dashboards
- Generate actionable lending insights

---

## Tech Stack

- Python
- SQL
- Tableau
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---
## Dataset

**Source:**
LendingClub Accepted Loans Dataset (Kaggle)

- 225K+ loan records analyzed
- 11 key financial attributes
- Loan amount
- Interest rate
- Annual income
- Debt-to-income ratio
- FICO score
- Loan grade
- Loan purpose
- Loan status
- State
- Loan term

---

## Project Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Portfolio Analytics
      │
      ▼
Credit Risk Segmentation
      │
      ▼
Default Prediction
      │
      ▼
Tableau Dashboard
```

---

# Exploratory Data Analysis

The project analyzes:

- Loan Grade Distribution
- Loan Status Distribution
- Borrower Purpose Analysis
- Geographic Loan Distribution
- Interest Rate Analysis
- Credit Risk Segmentation
- Portfolio Exposure

---

# Machine Learning

Model Used:

- Logistic Regression

Target Variable:

- Default Flag

Features Used:

- Loan Amount
- Interest Rate
- Annual Income
- Debt-to-Income Ratio
- FICO Score
- Loan Grade
- Loan Purpose
- Loan Term

---

# Tableau Dashboard

The dashboard provides interactive monitoring of:

### Executive KPIs

- Total Loans
- Total Loan Amount
- Average Interest Rate
- Default Rate

### Visualizations

- Loan Grade Distribution
- Portfolio Risk Segmentation
- Loan Status Analysis
- Geographic Distribution
- Loan Purpose Analysis

Interactive filters include:

- Loan Grade
- Loan Purpose
- State
- Loan Term

---

#  Repository Structure

```
loan-portfolio-intelligence-system/
│
├── data/
│   └── loan_portfolio_clean.csv
│
├── notebooks/
│   └── Loan_Portfolio_Analysis.ipynb
│
├── dashboard/
│   ├── LoanPortfolioDashboard.twbx
│   └── dashboard.png
│
├── sql/
│   └── business_queries.sql
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

#  Business Insights

- Identified high-risk borrower segments using credit grades and FICO scores.
- Analyzed portfolio concentration across loan purposes and geographic regions.
- Monitored portfolio health through executive KPIs and interactive dashboards.
- Built a baseline predictive model for loan default classification.

---

#  Future Improvements

- XGBoost and Random Forest models for improved prediction
- SHAP-based model explainability
- Time-series portfolio monitoring
- Automated ETL pipeline
- Real-time dashboard integration

---

# 👩‍💻 Author

**Khushi Parekh**

GitHub: https://github.com/KhushiParekh28

LinkedIn: https://www.linkedin.com/in/parekhkhushi

---
