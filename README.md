# Customer-Churn-Analysis
This project presents an end-to-end churn analysis workflow, leveraging SQL for data preparation and Tableau for interactive dashboard development. The objective is to identify churn drivers, quantify revenue risk, and generate actionable retention strategies that directly impact recurring revenue.

Data Source:
This analysis utilizes the IBM Telco Customer Churn Dataset, available on Kaggle.
IBM Kaggle Dataset: [IBM Customer Churn](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset)

🚀 How to Run the Analysis
1. Install DuckDB.
2. Download the Olist dataset from the Kaggle link above.
3. Ensure that the data folder is a directory below the database file.
4. Run CMD in the directory line where the folder is located
5. Type duckdb 'project-name'.db -ui
   
It will then move you to Duckdb to reproduce all KPIs and views. Ensure that the 'Environment Setup' section is executed first to ingest the CSVs into tables.

## Business Objective

This analysis evaluates customer churn behavior across 7,043 customers to:
Measure overall churn rate
Quantify revenue at risk
Identify high-risk customer segments
Provide data-driven retention recommendations

## 📊 Key Performance Indicators (KPIs)
Overall Churn Rate: 26.54%
Total Customers Analyzed: 7,043
Revenue at Risk: $139,131 per month

## Key Insights & Strategic Findings
1️⃣ Contract Type Risk Analysis
Month-to-month contracts show a 42.7% churn rate
One-year contracts: 11.3%
Two-year contracts: 2.8%

Customers on flexible contracts are ~4x more likely to churn compared to long-term subscribers.

Tenure-Based Churn Risk
0–6 months: 52.9% churn
6–12 months: 35.9%
12–24 months: 28.7%
24+ months: 14.0%

More than half of churn occurs within the first 6 months.

[View Executive Dashboard](https://public.tableau.com/views/CustomerChurnRetentionInsightsDashboard_17704637220150/CustomerChurnRetentionOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Recommendations
Strengthen onboarding programs within the first 90 days
Introduce incentives for long-term contract conversion
Deploy targeted retention campaigns for month-to-month subscribers
