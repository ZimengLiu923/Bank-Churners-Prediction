# Credit Card Customer Churn Prediction

This repository contains the analysis and findings of a machine learning project aimed at predicting customer attrition for a credit card company. The goal was to identify potential attrited customers to enable the bank to take proactive measures to retain them.

## Dataset
The dataset used in this analysis is the Credit Card Customers dataset, originally posted by Sakshi Goyal on Kaggle. The dataset contains 10,127 sample units and 20 variables after preprocessing. The dataset can be downloaded [here](https://github.com/ZimengLiu923/Bank-Churners-Prediction/blob/main/BankChurners.csv).

## Context
In this project, I conducted a classification analysis to predict customer attrition using various machine learning models. The goal was to accurately classify customers as either attrited or existing, based on a range of predictors.

Key information about the project:

- Data Preprocessing: Conducted data cleansing tasks and applied over-sampling and under-sampling techniques to create a balanced training set.
- Response Variable: The response variable, Attrition_Flag, was binary, indicating whether a customer is an attrited customer (1) or an existing customer (0).
- Models Used: The analysis involved several models, including Decision Tree, Bagging, Boosting, Logistic Regression, and Support Vector Machine (SVM).

## Findings
The bagging model was identified as the most effective for predicting customer attrition, due to its superior performance in terms of accuracy and error rate.
