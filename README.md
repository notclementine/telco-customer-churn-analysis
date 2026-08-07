Telco Customer Churn Analysis

Customer churn analysis for ABC Communications Ltd, a fictional telecom company, built as part of the **AnalystLab Africa Data Analytics Internship Programme (Week 1)**.

## Business Problem

ABC Communications is losing customers at a significant rate — a 26.5% overall churn rate, or roughly 1 in 4 customers. This project investigates *who* is churning, *why*, and what retention strategies could reduce it.

## Links
📊 Presentation (Google Slides): https://docs.google.com/presentation/d/14Kgv0QoTla0rxX7QKc8DvO4_F_xR9RolfbFuEWYMZjE/edit?usp=sharing

💼 LinkedIn Post:

## Dataset

- **Source:** [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- 7,043 customers, 21 attributes covering demographics, account details, subscribed services, and churn outcome

## Methodology

1. **Data Cleaning & Inspection** — identified and fixed a hidden data quality issue in TotalCharges (blank strings instead of true nulls for new customers), verified no duplicates or other missing values
2. **Exploratory Analysis** — 9 visualizations (bar charts, pie charts, histograms, box plot, correlation heatmap) built with pandas and Plotly
3. **Insight Generation** — cross-referenced findings across multiple charts to identify consistent churn drivers
4. **Business Recommendations** — translated findings into actionable retention strategies

## Key Findings

- **Contract type is the strongest churn driver** — month-to-month customers churn at ~43%, vs. ~11% (one-year) and ~3% (two-year)
- **Churn follows a "bathtub" pattern** — highest risk in a customer's early months, with strong long-term loyalty afterward (tenure showed the strongest correlation with churn: -0.35)
- **Fiber optic customers churn over 2x the rate of DSL customers** (~42% vs ~19%)
- **Electronic check users churn dramatically more** than customers on automatic payment methods (~45% vs 15-19%)
- **Senior citizens are a small but high-risk segment** — only 16% of customers, but churning at ~42%, nearly double the rest of the base

## Recommendations

1. Offer incentives for longer-term contract commitments
2. Launch a "first 90 days" retention program for new customers
3. Investigate Fiber optic pricing and service satisfaction
4. Migrate customers from electronic check to automated payment methods
5. Build a dedicated senior citizen support pathway
6. Bundle value-added services to improve perceived value

## Repository Structure

```
telco-customer-churn-analysis/
├── README.md
├── notebook/
│   └── telco-churn-analysis.ipynb
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── reports/
    ├── Business_Understanding_Report.docx
    ├── Dataset_Inspection_Report.docx
    └── Business_Insights.docx
```

## Tools Used

- Python (pandas, Plotly)
- Jupyter Notebook
- Google Slides (presentation)

## Author

**Nestor Clementina Aniebiet-Abasi**
Data Analytics Intern, AnalystLab Africa
[GitHub](https://github.com/notclementine)
