# Module 20 Report Template

## Overview of the Analysis
In this review, historical data on loans is analyzed using machine learning to determine the likelihood that a predicted loan will default based on several factors. These factors include loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt.

This analysis was conducted by taking the historical data and splitting it into a training set and testing set, randomly. A Logistic Regression Model was used on the training data. The test data was then used to make a set of prediction. These predictions were compared to the original set of data to determine an accuracy score, confusion matrix, and classification report.

## Results
* Machine Learning Model 1 (Logistic Regression):
  * Accuracy Score of .9442 (or 94.42%)
  * Precision Score of 1.00 (or 100%) for the healthy loans
  * Precision Score of .87 (or 87%) for the high-risk loans
  * Recall Score of 1.00 (or 100%) for the healthy loans
  * Recall Score of .89 (or 89%) for the high-risk loans
  
* Machine Learning Model 2 (Logistic Regression with Random Over Sampler):
  * Accuracy Score of .9941 (or 99.41%)
  * Precision Score of .99 (or 99%) for the healthy loans
  * Precision Score of .99 (or 99%) for the high-risk loans
  * Recall Score of .99 (or 99%) for the healthy loans
  * Recall Score of .99 (or 99%) for the high-risk loans

## Summary
The Logistic Regression Model with the Random Oversampler would be recommended for use. The number of False Negatives and False Positives each have less than 350 results. The accuracy rate is 99.4%, which is remarkably high. The precision and recall were both at 99%. This module is highly accurate at predicting if a loan will be high risk or healthy.
