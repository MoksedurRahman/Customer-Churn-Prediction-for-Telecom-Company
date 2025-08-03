# Customer-Churn-Prediction-for-Telecom-Company
Predicting which customers are likely to leave a telecom service using machine learning.

## Problem Statement
Telecom companies experience customer churn (attrition) which impacts revenue. Early identification of at-risk customers allows for targeted retention efforts.

## Dataset
IBM Telco Customer Churn Dataset containing:
- 7,043 customer records
- 20 features (demographic, account, and service information)
- Binary target variable (Churn: Yes/No)

## Methodology
1. Exploratory Data Analysis
2. Feature Engineering
3. Model Training & Evaluation
4. Hyperparameter Tuning
5. Model Interpretation

## Results
Best performing model: XGBoost with 0.82 AUC score

| Model               | Accuracy | Precision | Recall | F1-score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.78     | 0.65      | 0.53   | 0.58     |
| Random Forest       | 0.80     | 0.72      | 0.58   | 0.64     |
| XGBoost             | 0.81     | 0.75      | 0.61   | 0.67     |

## How to Run
1. Clone repository
2. Install requirements: `pip install -r requirements.txt`
3. Run notebooks in sequence