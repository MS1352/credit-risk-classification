# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to predict the credit risk of loans using financial data. The dataset included features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable was the "loan_status," where 0 indicates a healthy loan and 1 indicates a high-risk loan.

We used Logistic Regression, a binary classification model, to predict the likelihood of a loan being high-risk based on the provided financial features. The process involved data preprocessing, splitting the data into training and testing sets, training the model, and evaluating its performance

## Results

Logistic Regression
Accuracy: 99%
Precision:
Class 0 (Healthy Loan): 1.00
Class 1 (High-Risk Loan): 0.84
Recall:
Class 0 (Healthy Loan): 0.99
Class 1 (High-Risk Loan): 0.94
F1-score:
Class 0 (Healthy Loan): 1.00
Class 1 (High-Risk Loan): 0.89

## Summary

The Logistic Regression model performed exceptionally well, achieving high accuracy and strong precision and recall for both healthy and high-risk loans. The model is suitable for deployment due to its simplicity and effectiveness. It is particularly good at identifying healthy loans (class 0) with perfect precision and high recall, while also effectively identifying high-risk loans (class 1). The high recall for high-risk loans is critical, as it ensures that most high-risk loans are correctly identified, minimizing potential financial loss.

Given the model's performance, it is recommended for use in predicting credit risk. Further refinements or additional models could be explored if even higher recall or precision is needed for high-risk loans.
