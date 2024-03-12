# Credit Risk Analysis Report
## Overview of the Analysis

The purpose of the analysis is to predict whether a loan is healthy or high-risk based on financial data. The aim is to develop a machine learning model to assess the credit risk of borrowers using historical lending data from a peer-to-peer lending services company. The purpose was to predict the creditworthiness of borrowers based on various financial indicators provided in the dataset.
The dataset contains information on loan status, including whether a loan is healthy or high-risk. We needed to predict the loan status based on other features such as loan amount, interest rate, debt-to-income ratio, and employment length.

The loan status variable includes two categories:

•	Healthy Loan (0)

•	High-Risk Loan (1)

The machine learning process involved the following stages:
1.	Data preprocessing: Exploring the dataset, handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
2.	Model training: Building a logistic regression model using the training data.
3.	Model evaluation: Assessing the performance of the trained model using accuracy, precision, and recall metrics.

## Results
•	Logistic Regression Model:

•	Accuracy Score: 0.99

•	Precision Score (Healthy Loan): 1.00

•	Precision Score (High-Risk Loan): 0.85

•	Recall Score (Healthy Loan): 0.99

•	Recall Score (High-Risk Loan): 0.91

## Summary
The logistic regression model performed exceptionally well in predicting credit risk based on the provided dataset. It achieved an accuracy score of 0.99, indicating near-perfect performance in classifying loans.
The precision score for healthy loans was perfect (1.00), indicating that all loans predicted as healthy were indeed healthy. For high-risk loans, the precision score was 0.85, implying that 85% of loans predicted as high-risk were correctly identified.

Similarly, the recall score for healthy loans was high at 0.99, indicating that the model correctly identified 99% of actual healthy loans. For high-risk loans, the recall score was 0.91, signifying that 91% of actual high-risk loans were correctly classified.

Considering the high accuracy, precision, and recall scores, the logistic regression model is recommended for use by the peer-to-peer lending services company to assess the creditworthiness of potential borrowers. It effectively identifies both healthy and high-risk loans, making it a valuable tool for risk assessment in lending practices.

