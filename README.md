### credit-risk-classification

## Overview of the Analysis

Logistic Regression model for loan risk prediction was analyzed to see how well the model performed by studying the balanced accuracy score, confusion matrix, and classification report.

Features for the machine learning model are:
	-Loan Size
	-Interest Rate
	-Borrower Income
	-Debt to Income
	-Number of Accounts
	-Derogatory Marks
	-Total Debt

Target for the machine learning model is:
	-Loan status

Data size (Number of rows): 77536

Stages of ML process:
	-Upload and read data
	-Separate target from features
	-Split data to test/train sets
	-Fit and Predict using Logistic Regression model
	-Provide Balanced Accuracy Score, Confusion Matrix, and Classification Report
	-Re Fit and Predict using Logistic Regression model and Random Over Sampler
	-With new model, provide Balanced Accuracy Score, Confusion Matrix, and Classification Report

## Results

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
	-Balanced Accuracy Score: 0.9442676901753825
	-Confusion Matrix
	          Predicted 0  Predicted 1
	Actual 0        18679		80
	Actual 1           67		558
	
	-Classification Report
   	               precision    recall  f1-score   support
	
  	          0       1.00      1.00      1.00     18759
                  1       0.87      0.89      0.88       625

 	    accuracy                           0.99     19384
 	   macro avg       0.94      0.94      0.94     19384
	weighted avg       0.99      0.99      0.99     19384

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
	-Balanced Accuracy Score: 0.9959744975744975
	-Confusion Matrix
	          Predicted 0  Predicted 1
	Actual 0        18668           91
	Actual 1            2          623
	
	-Classification Report
   	           precision    recall  f1-score   support
	
  	                 0       1.00      1.00      1.00     18759
         	         1       0.87      1.00      0.93       625

 	    accuracy                           1.00     19384
 	   macro avg       0.94      1.00      0.96     19384
	weighted avg       1.00      1.00      1.00     19384

## Summary

* Machine Learning Model 2 was a better performing model by 4.2%
* Performance does depend on the problem we are trying to solve. For loan purposes, one would be better off predicting the high-risk loans properly so as to not have deficits in bank. 

