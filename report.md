# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this credit risk report is to create a model that would predict credit worthiness for borrowers trying to obtain a loan at the bank. By using linear regression, we were able to determine the accuracy, precision, and recall scores for healthy and high risk loans that were provided in the dataset. 
* The credit worthiness were based on a number of factors that were all found in the CSV that was provided: 
  - loan size (amount)
  - interest rate
  - borrower's income
  - debt to income ratio
  - total number of accounts
  - derrogatory marks found on credit
  - total debt
  - loan status. 
* The y value were the labels of the dataset and this was the target variable. This variable was classified as either a 0 or 1. The 0 represented a healthy loan and a 1 was represented as high-risk. The x variable were the features of the dataset. 
* The Stages of the Machine Learning Process that were performed in this report were: 
  - Gathering Data
  - Date Preparation
  - Data Wrangling 
  - Analyse Data
  - Train Model
  - Test Model 
  - Deployment 
* The Logistic Regression Model with resampling method were performed to observe the accuracy for the credit risk classification. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
      - Accuracy: 99%
  - Precision: for 0 100%, for 1 86% 
  - Recall scores: for 0 100%,  for 1 90%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

I wouldn't recommend this model as since it's the only model we have to go off of we can't really determine if this was the best fit for the task at hand. I would recommend running a few other models against each other to see where we are getting the best results from.
