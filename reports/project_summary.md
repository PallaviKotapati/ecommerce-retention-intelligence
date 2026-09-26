# E-Commerce Customer Retention & Revenue Intelligence

## Project Objective

Build an end-to-end customer analytics and machine learning solution
to identify customers at risk of churn, understand their behavior,
estimate potential revenue at risk, and prioritize customers for
retention actions.

## Key Components

- Customer-level feature engineering
- RFM-based customer segmentation
- Time-based churn prediction
- Logistic Regression
- Random Forest
- Churn probability estimation
- SHAP model explainability
- Customer risk categorization
- Expected revenue-at-risk estimation
- Retention priority scoring
- Interactive Power BI dashboard

## Business Questions

1. Which customers are likely to stop purchasing?
2. What behavioral factors are associated with churn?
3. Which customer segments generate the most revenue?
4. How much revenue is potentially at risk?
5. Which customers should be prioritized for retention?

## Technology Stack

Python
Pandas
NumPy
Scikit-learn
SHAP
Matplotlib
Seaborn
Power BI
DAX
Git/GitHub

## Dataset

Olist Brazilian E-Commerce Public Dataset.

The dataset contains information about customers, orders,
products, sellers, payments and reviews.

## Machine Learning Approach

Historical customer behavior was used to create customer-level
features. A time-based cutoff was used to define a future
90-day churn window, reducing the risk of temporal data leakage.

Models implemented:

- Logistic Regression
- Random Forest

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

## Explainability

SHAP was used to understand which customer behavioral features
contribute to Random Forest churn predictions.

## Business Intelligence

The final Power BI dashboard contains four sections:

1. Executive Overview
2. Customer Intelligence
3. Churn & Risk Analysis
4. Revenue & Retention

The dashboard allows users to explore customer segments,
risk levels, revenue exposure and retention priorities.

## Outcome

The project connects customer analytics and machine learning
with business decision-making by transforming churn predictions
into actionable customer-risk and revenue-risk insights.