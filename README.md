📊 Telco Customer Churn Analysis


📌 Project Overview

Customer churn is a critical challenge in the telecom industry. This project analyzes the Telco Customer Churn dataset (7,043 customers, 21 features) to identify patterns that drive customer attrition and to provide actionable recommendations for improving customer retention.

Using Python (Jupyter Notebook) and data visualization techniques, this analysis uncovers key factors influencing churn, builds insights into customer behavior, and proposes strategies for churn reduction.

📂 Repository Contents

Customer Churn.csv – Raw dataset containing customer information.

Telco.ipynb – Jupyter Notebook with complete analysis, data cleaning, visualization, and insights.

Telco customer Churn Analysis.pdf – Final report summarizing findings and business recommendations.



🔍 Key Findings

Overall churn rate: ~26–27%

Fiber Optic customers show highest churn (~42%) vs DSL (~18%).

Customers without value-added services (OnlineSecurity, TechSupport, OnlineBackup) churn at ~40–45%, while subscribers churn at only ~15–20%.

Contract type & tenure are strong predictors:

Month-to-month → ~43% churn

1–2 year contracts → <12% churn

Electronic check payment method has the highest churn (~45%).

High monthly charges (> $80) and short tenure (< 1 year) increase churn risk.



💡 Recommendations

Promote long-term contracts → Offer discounts or loyalty rewards to encourage 1–2 year plans.

Encourage auto-pay methods → Incentivize bank transfers/credit card auto-pay over electronic checks.

Bundle value-added services → Integrate OnlineSecurity, TechSupport, and OnlineBackup with internet plans.

Focus on Fiber Optic customers → Address service quality, pricing, and complaints to reduce churn.

Engage new customers early → Onboarding, welcome discounts, and priority support for customers in their first year.

Monitor high-paying customers → Offer loyalty perks to those with >$80 monthly charges.



🛠️ Tools & Libraries

Python: pandas, numpy, matplotlib, seaborn

Jupyter Notebook for analysis

PDF report for business insights



🚀 How to Use

Clone this repository:

git clone https://github.com/your-username/telco-churn-analysis.git
cd telco-churn-analysis


Install dependencies (if required):

pip install -r requirements.txt


Open the Jupyter Notebook:

jupyter notebook Telco.ipynb


Explore the dataset (Customer Churn.csv) and follow the analysis workflow.



📈 Results

This project provides both technical insights (exploratory data analysis, feature importance) and business strategies to reduce churn. By focusing on contract structure, payment methods, and bundled services, Telco companies can significantly improve customer retention.
