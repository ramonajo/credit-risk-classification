# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

This analysis was done to determine which loans are healthy and which are high-risk, based on factors such as loan size, interest rate, and total debt. To do so, I created a linear regression model that used this information to predict the status of the loan, and then to determine how accurate the model was. 
  
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
  
* Describe the stages of the machine learning process you went through as part of this analysis.
  separate loan status from the rest of the features, test/train dataset, create logistic regression model
  (look in slides for this one lol)
  
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
  linear regression, train_test_split, 

## Results
* Accuracy: 99%
* Precision (healthy, 0): 100%
* Precision (high-risk, 1):100%
* Recall (healthy, 0): 87%
* Recall (high-risk, 1): 89%

## Summary
The logistic regression model does a very good job of predicting the loans, particularly the healthy loans. It is less accurate when predicting the high risk loans, which unfortunately, it is more important to correctly predict. 