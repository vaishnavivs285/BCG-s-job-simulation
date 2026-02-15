# Customer Churn Prediction for PowerCo

**BCG Data Science Virtual Experience --- Forage (Feb 2026)**

------------------------------------------------------------------------

# Business Problem

PowerCo, a major gas and electricity utility provider, was experiencing
increased customer churn. Customer churn leads to significant revenue
loss because acquiring new customers is far more expensive than
retaining existing ones.

The business needed a data-driven solution to:

-   Identify key drivers of churn
-   Predict customers likely to churn
-   Enable proactive retention strategies

------------------------------------------------------------------------

# Project Objective

The objective of this project was to build a machine learning model to
predict customer churn and identify key features influencing churn
behavior.

This allows the company to intervene early and reduce customer loss.

------------------------------------------------------------------------

# Dataset Overview

The dataset included:

-   Customer information
-   Energy consumption data
-   Pricing data
-   Contract and tenure information
-   Churn label (Target Variable)

Target Variable: - churn → 1 (Customer left), 0 (Customer retained)

------------------------------------------------------------------------

# Project Pipeline

The project followed a structured machine learning workflow:

1.  Business Understanding
2.  Data Cleaning
3.  Exploratory Data Analysis (EDA)
4.  Feature Engineering
5.  Model Building
6.  Model Evaluation
7.  Business Insights

------------------------------------------------------------------------

# Exploratory Data Analysis (EDA)

EDA was performed to understand customer behavior patterns.

Key findings:

-   Customers with lower consumption were more likely to churn
-   Customers with shorter tenure had higher churn rates
-   Pricing sensitivity influenced churn
-   Class imbalance existed between churned and retained customers

EDA helped identify useful features for modeling.

------------------------------------------------------------------------

# Feature Engineering (Critical Step)

Feature engineering transformed raw data into meaningful predictive
features.

Key engineered features:

## 1. Customer Tenure

Calculated from activation date.

Why important: Longer-tenure customers are less likely to churn.

## 2. Contract Remaining Duration

Customers near contract expiration have higher churn probability.

## 3. Price Sensitivity Feature

Difference between peak and off-peak prices.

Helps capture customer sensitivity to pricing.

## 4. Consumption Behavior Features

Consumption trends help identify disengaged customers.

## 5. Categorical Encoding

Converted categorical variables into numeric format using encoding
techniques.

Feature engineering significantly improved model performance.

------------------------------------------------------------------------

# Model Selection

Model used: Random Forest Classifier

Why Random Forest:

-   Handles non-linear relationships
-   Robust to noise and overfitting
-   Handles mixed data types
-   Provides feature importance
-   Performs well on structured business data

Class imbalance handled using:

class_weight = "balanced"

------------------------------------------------------------------------

# Model Evaluation

Evaluation Metric Used: Recall Score

Result: Recall = 50%

Meaning: The model successfully identified 50% of customers who actually
churned.

Recall is critical because missing churn customers results in business
loss.

------------------------------------------------------------------------

# Feature Importance Insights

Key churn drivers identified:

-   Customer tenure
-   Energy consumption
-   Pricing features
-   Contract duration

These insights help business teams design retention strategies.

------------------------------------------------------------------------

# Business Impact

This solution enables PowerCo to:

-   Predict customers at risk of churn
-   Take preventive retention actions
-   Improve customer retention
-   Increase revenue stability

------------------------------------------------------------------------

# Tools and Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn
-   Random Forest

------------------------------------------------------------------------

# Key Skills Demonstrated

-   Data Cleaning
-   Exploratory Data Analysis
-   Feature Engineering
-   Machine Learning
-   Model Evaluation
-   Business Problem Solving
-   Predictive Modeling

------------------------------------------------------------------------

# Conclusion

This project successfully built a churn prediction system using machine
learning and identified key factors influencing customer churn. The
insights generated can help PowerCo reduce churn and improve business
performance.

------------------------------------------------------------------------


