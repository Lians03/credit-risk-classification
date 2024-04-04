# credit-risk-classification

## Overview

In this analysis, the primary objective was to leverage machine learning models, specifically logistic regression, to predict the creditworthiness of borrowers based on historical lending data from a peer-to-peer lending services company. The dataset comprised financial information such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt, with the goal to classify loans into "healthy" (low risk) or "high-risk" loans, as indicated by the loan_status variable. This process involved several key stages, including data preprocessing (handling missing values, encoding categorical variables, etc.), feature selection to identify the most relevant variables, splitting the dataset into training and testing sets, and finally, training and evaluating the logistic regression model. The evaluation metrics of interest were accuracy, precision, recall, and the F1 score, which provided insights into the model's performance in accurately predicting loan risk.

## Results

### Machine Learning Model Performance
Machine Learning Model 1: Logistic Regression
Description of Model 1 Accuracy, Precision, and Recall scores:
#### Accuracy: 
The logistic regression model achieved a overall accuracy of 0.99.
#### Low-Risk (Healthy) Loan Predictions:
Precision: 1.00
Recall: 0.99

#### High-Risk Loan Predictions:
Precision: 0.85
Recall: 0.91

## Summary
Given the model's performance, it is highly effective, especially in identifying low-risk loans with almost perfect precision and recall. Although it slightly underperforms in predicting high-risk loans, it demonstrates strong recall. Considering high-risk loans are more critical for managing financial risk and potential defaults, the model's ability to identify a significant majority of these loans makes it particularly valuable. The logistic regression model is recommended here and its particularly well-suited for credit risk analysis because it excels with categorical (discrete) outcomes like loan default status, making it ideal for analyzing discontinuous data to predict binary outcomes.
