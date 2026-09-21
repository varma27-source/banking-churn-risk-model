# banking-churn-risk-model
Predictive machine learning pipeline using Random Forest to identify banking customer churn risk and analyze key retention drivers.

# Predictive Customer Churn Risk Model for Banking Services

## Project Overview
This project develops an end-to-end predictive machine learning pipeline designed to flag banking and credit card customers at risk of attrition. By identifying early warning signals, financial institutions can deploy proactive retention interventions to protect client capital and reduce customer acquisition costs.

## Methodology
- **Data Ingestion & Cleaning:** Ingested multi-variable customer records (credit score, balance, tenure, product count, active status). Removed uninformative identifiers and applied one-hot encoding to categorical dimensions.
- **Predictive Modeling:** Implemented a Random Forest Classifier evaluated across stratified training/test splits.
- **Performance Evaluation:** Validated retention classifications using precision, recall, F1-score, and confusion matrix diagnostics.
- **Feature Attribution:** Extracted feature importance metrics to identify the primary commercial drivers behind customer exits (e.g., account age, number of active products, balance levels).

## Key Business Insights & Implications
- **Product Concentration:** Customers holding multiple banking products show significantly lower attrition rates.
- **Engagement Thresholds:** Inactive membership combined with high account balances represents the highest value-at-risk segment, warranting targeted relationship-manager outreach.

## Tech Stack
Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
