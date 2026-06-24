# Customer Segmentation and Churn Prediction

## About This Project

I built this project to explore customer behavior and understand what factors contribute to customer churn. While predicting churn was the primary goal, I also wanted to uncover patterns in customer data that could help businesses improve customer retention.

The project includes data cleaning, exploratory data analysis, customer segmentation, feature preprocessing, and machine learning models for churn prediction.

---

## Problem Statement

Customer churn is a major challenge for subscription-based businesses. Losing existing customers directly impacts revenue and often costs more than retaining them.

The objective of this project is to:

- Identify customers who are likely to churn.
- Understand the characteristics of churned customers.
- Segment customers based on similarities in behavior.
- Generate insights that could support retention strategies.

---

## Dataset

The dataset contains customer-related information such as:

- Gender
- Senior Citizen Status
- Partner and Dependents
- Tenure
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

Target Variable:

**Churn**
- Yes → Customer left the service
- No → Customer stayed with the service

---

## Dataset

I used IBM's Telco Customer Churn dataset, a widely used benchmark dataset for customer retention and churn analysis.

Source:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains information for 7,043 telecom customers, including demographics, subscribed services, contract information, billing details, and whether the customer eventually churned.

---

## Dataset Snapshot

- Total Customers: 7,043
- Features: 20+
- Churn Rate: 26.5%
- Retained Customers: 73.5%
- Missing Values: Handled during preprocessing

### Distribution

| Class | Count |
|---------|---------|
| No Churn | 5,174 |
| Churn | 1,869 |


## Workflow

### 1. Data Cleaning

- Checked for missing values
- Handled inconsistent data types
- Removed unnecessary information
- Prepared data for analysis

### 2. Exploratory Data Analysis

Some of the questions explored:

- How is churn distributed?
- Which contract types have higher churn?
- Does tenure affect churn?
- Do payment methods influence customer retention?
- What role do monthly charges play?

### 3. Feature Preprocessing

- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Data preparation for machine learning models

### 4. Customer Segmentation

Customer groups were created to identify common behavioral patterns and service usage trends.

### 5. Churn Prediction

Several machine learning models were trained and evaluated to classify customers as:

- Churn
- Non-Churn

---

## Key Observations

A few patterns that stood out during analysis:

- Customers with month-to-month contracts were more likely to leave.
- Longer-tenure customers generally had lower churn rates.
- Customers paying higher monthly charges showed increased churn tendencies.
- Certain payment methods appeared more common among churned customers.

These observations may help businesses design more targeted retention strategies.

---

## Interesting Findings

- Customers with month-to-month contracts showed a churn rate of approximately 43%.
- Customers on two-year contracts had churn rates below 5%.
- Churned customers had higher average monthly charges than retained customers.
- Tenure was one of the strongest indicators of customer retention.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---


## What I Learned

Working on this project helped me gain practical experience with:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Customer Segmentation
- Classification Models
- Model Evaluation
- Translating data into business insights

---

## Future Improvements

Some ideas I may explore in the future:

- Hyperparameter tuning using Optuna
- Explainable AI using SHAP
- Streamlit deployment
- Automated model retraining
- Additional ensemble techniques

