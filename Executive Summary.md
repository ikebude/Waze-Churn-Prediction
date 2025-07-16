### 📊 Executive Summary: Initial Waze Churn Dataset Analysis
🧾 Objective
This project aims to help Waze understand and prevent monthly user churn by identifying key factors that influence whether users continue using the app or stop. Early analysis is focused on organizing and summarizing the dataset to prepare for exploratory data analysis (EDA) and predictive modeling.

✅ Key Highlights
1. Dataset Overview:

Rows: 14,999 users

Columns: 13 features (including target label: retained or churned)

Data Types: Mostly numerical (e.g., sessions, drives, kilometers), with some categorical (e.g., device, label)

2. Churn Indicators:

Users with 0 sessions, drives, or activity days may represent immediate churn risk.

Metrics like driven kilometers, navigation usage, and driving days show high variability, suggesting they could be important features for predicting churn.

3. Engagement Patterns:

Median user has about 56 sessions, 48 drives, and 12 driving days per month.

The mean n_days_after_onboarding is ~1,750 days (~4.8 years), which indicates many users have long-standing app usage histories—valuable for retention strategies.

🧠 For Technical Team (Data & Analytics):
Features are well-structured for building a predictive model.

Target column label is categorical and ready for binary classification.

Next recommended steps: Encode categorical variables, check for class imbalance, and begin EDA on behavioral differences between retained and churned users.

💼 For Cross-functional Stakeholders:
We are laying the foundation for identifying who is likely to churn, why, and when.

These insights will guide user engagement strategies (e.g., in-app offers, retention campaigns).

Improving retention even by a small margin can lead to measurable gains in app growth and user satisfaction.