# Module 20 Report Template

## Overview of the Analysis

This analysis was done to determine which loans are healthy and which are high-risk, based on factors such as loan size, interest rate, and total debt. To do so, I created a linear regression model that used this information to predict the status of the loan, and then to determine how accurate the model was.  

After separating the loan status from the rest of the features, I used train_test_split to create two datasets, which allows for measuring the performance of the model against a dataset that has not been trained. I then created a linear regression model using the training data, and compared them to the testing data. To verify the model's accuracy, I created a confusion matrix, which describes the false positives and false negatives of the model. The classification report similarly measures a model's accuracy by evaluating the predicted occurances for each class - precision, recall, and accuracy. Both the confusion matrix and the classification report showed that the linear regression model was successful in predicting the status of a loan.


## Results
* Accuracy: 99%
* Precision (healthy, 0): 100%
* Precision (high-risk, 1):100%
* Recall (healthy, 0): 87%
* Recall (high-risk, 1): 89%

## Summary
The logistic regression model does a very good job of predicting the loans, particularly the healthy loans. It is less accurate when predicting the high risk loans, which unfortunately, it is more important to correctly predict. 