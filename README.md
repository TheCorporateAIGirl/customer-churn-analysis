# Customer Churn Analysis

## Project Overview
This project presents an end-to-end customer churn analysis using real customer
subscription and usage data. The goal is to identify churn drivers, build
predictive models, and provide actionable business recommendations to improve
customer retention.

## Business Problem
Customer churn occurs when customers discontinue their subscriptions.
Churn directly impacts revenue, customer lifetime value, and business growth.

The objective of this project is to:
- Predict customers likely to churn
- Understand the key drivers of churn
- Recommend data-driven retention strategies

## Dataset
- Source: Public churn dataset shared for analytics mentorship
- Records: ~7,000 customers
- Features: Customer demographics, subscription details, usage patterns
- Target Variable: `Churn` (Yes / No)

Dataset link: https://lnkd.in/erDSyNV7

## Methodology
1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature engineering
4. Baseline modeling (Logistic Regression)
5. Advanced modeling (Random Forest)
6. Model evaluation (Recall, Confusion Matrix, ROC-AUC)
7. Postdictive error analysis
8. Business recommendations

## Key Insights
- Month-to-month contract customers have the highest churn risk
- High monthly charges relative to tenure increase churn likelihood
- Long tenure does not guarantee customer retention

## Model Evaluation
- Logistic Regression used as a baseline
- Random Forest used for advanced modeling
- Class imbalance handled using class weighting
- Recall prioritized due to higher business cost of missed churners
- ROC-AUC used to evaluate ranking performance

## Business Recommendations
- Incentivize month-to-month customers to switch to long-term contracts
- Offer proactive support to high-charge customers
- Trigger retention campaigns at key tenure milestones

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SHAP

## Author
**Famiwaye Oluwatobiloba Omowunmi**  
Aspiring Data Scientist

