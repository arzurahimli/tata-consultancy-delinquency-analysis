# 📊 Credit Card Delinquency Risk Analysis — Tata iQ × Geldium Finance

> An end-to-end data analytics and AI/ML project simulating a real-world consulting engagement at **Tata iQ**, focused on reducing credit card delinquency through exploratory data analysis, predictive modeling, and actionable intervention strategies.

---

## 🧭 Project Overview

**Client:** Geldium Finance (simulated financial services company)  
**Team:** Tata iQ Analytics Consulting  
**Role:** AI Transformation Consultant — Data Analysis & Modeling

Geldium Finance faced a rising credit card delinquency rate and needed a data-driven framework to identify at-risk customers early and deploy targeted interventions. This project delivers:

- A thorough **Exploratory Data Analysis (EDA)** of customer credit behavior
- A **predictive modeling framework** using XGBoost for delinquency classification
- A **recommendation strategy** for the Head of Collections
- An **interactive dashboard** for business decision-making

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `Delinquency_prediction_dataset.xlsx` | Raw customer dataset with credit and payment features |
| `EDA_SummaryReport_Geldium.docx` | Full EDA report with data quality findings and risk indicators |
| `Updated_Business_Summary_Report_Geldium.docx` | Executive summary with business recommendations |
| `Task 2_ModelPlan_Geldium.docx` | ML model planning document — feature selection, approach, ethics |
| `xgboost_delinquency_framework.py` | XGBoost model implementation for delinquency prediction |
| `Geldium_EDA_Dashboard.html` | Interactive HTML dashboard for exploring key metrics |
| `Presentation_Geldium.pptx` | Stakeholder presentation deck |

---

## 🔍 Key Findings from EDA

- **High credit utilization (>80%)** is the strongest early indicator of delinquency
- **Missing payment history** in ~12% of records — imputed using median strategy
- **Customers with 3+ missed payments** in the past 6 months show 4× higher delinquency risk
- **Income-to-debt ratio** revealed a clear segmentation between low-risk and high-risk customers
- Anomalies detected in credit limit fields — values of $0 flagged for review

---

## 🤖 Modeling Approach

**Algorithm:** XGBoost (Gradient Boosted Trees)  
**Target Variable:** Binary delinquency flag (30+ days past due)

**Top Predictive Features:**
1. Payment history (last 6 months)
2. Credit utilization rate
3. Number of delinquent accounts
4. Debt-to-income ratio
5. Account age

**Evaluation Metrics:** Precision, Recall, F1-Score, AUC-ROC  
**Ethics Consideration:** Model outputs reviewed for bias across demographic segments to ensure responsible AI deployment.

---

## 📈 Intervention Recommendations

| Risk Tier | Profile | Recommended Action |
|-----------|---------|-------------------|
| High Risk | 3+ missed payments, utilization >80% | Immediate outreach, payment plan offer |
| Medium Risk | 1–2 missed payments, utilization 50–80% | Proactive SMS/email reminders |
| Low Risk | No missed payments, utilization <50% | Preventive financial wellness content |

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Excel](https://img.shields.io/badge/Excel-Dataset-217346?logo=microsoft-excel)
![PowerPoint](https://img.shields.io/badge/PowerPoint-Presentation-B7472A?logo=microsoft-powerpoint)

- **Python** — XGBoost, pandas, scikit-learn
- **Excel** — Data exploration and profiling
- **HTML/CSS** — Interactive EDA dashboard
- **Word/PowerPoint** — Business reporting and stakeholder communication
- **GenAI (Claude)** — EDA acceleration, imputation strategy, insight generation

---

## 🏗️ Project Structure

```
├── Delinquency_prediction_dataset.xlsx   # Raw data
├── EDA_SummaryReport_Geldium.docx        # EDA report
├── Updated_Business_Summary_Report_Geldium.docx  # Executive summary
├── Task 2_ModelPlan_Geldium.docx         # Model plan
├── xgboost_delinquency_framework.py      # ML model code
├── Geldium_EDA_Dashboard.html            # Interactive dashboard
├── Presentation_Geldium.pptx             # Stakeholder deck
└── README.md
```

---

## 🎯 Business Impact

This analysis framework enables Geldium Finance to:
- **Prioritize** collection resources on highest-risk customers
- **Reduce** unnecessary outreach to low-risk customers by ~40%
- **Increase** early intervention effectiveness through data-backed segmentation
- **Ensure** ethical, explainable AI use in financial decision-making

---

## 👩‍💼 About

This project was completed as part of the **Tata iQ Data Analytics Virtual Experience Program**, simulating a real consulting engagement with a financial services client.

**Author:** Arzu Rahimli  
**LinkedIn:** [linkedin.com/in/arzu-rahimli](https://linkedin.com/in/arzu-rahimli)  
📧 rahimleearzu@gmail.com

---

