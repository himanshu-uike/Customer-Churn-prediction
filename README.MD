# 📊 Customer Churn Prediction & Retention Analysis

## 🔍 Project Overview

This project aims to predict customer churn in a telecom dataset and
identify key factors influencing customer retention. The goal is to help
businesses proactively reduce revenue loss by identifying high-risk
customers.

## 🎯 Problem Statement

Customer churn leads to significant revenue loss.
This project builds a machine learning model to: - Predict whether a
customer will churn
- Identify key drivers of churn
- Provide actionable business insights

## 📁 Dataset

-   Dataset: Telco Customer Churn Dataset
-   ~7,000 customer records

## 🧹 Data Cleaning & Preprocessing

-   Handled hidden missing values in TotalCharges
-   Converted Churn into binary (0/1)
-   Removed customerID
-   One-hot encoding applied

## 📊 Exploratory Data Analysis (EDA)

-   Dataset is imbalanced
-   Low tenure → higher churn
-   High monthly charges → higher churn
-   Month-to-month contracts → highest churn

## 🤖 Model Building

Models used: - Logistic Regression
- Random Forest

## ⚙️ Model Optimization

-   Threshold tuning improved recall from 0.52 → 0.73

## 📈 Model Comparison

-   Logistic Regression (Tuned) selected due to better recall and
    simplicity

## 🔍 Feature Importance

Top features: - Contract type
- Monthly charges
- Tenure

## 💡 Business Insights

-   Month-to-month customers churn more
-   High charges increase churn
-   New customers are high-risk

## 🏁 Conclusion

The model helps identify high-risk churn customers and enables proactive
retention strategies.

## 🚀 Tech Stack

-   Python, Pandas, NumPy
-   Seaborn, Matplotlib
-   Scikit-learn

## 📌 Skills

-   Data Cleaning
-   EDA
-   ML Modeling
-   Evaluation & Optimization
