# Machine Learning Model: Performance Report

## Overview of the Analysis
* Purpose of the analysis: 
Credit risk classification analysis using a machine learning model serves multiple purposes such as risk assessment, decision making, interest rate derminations, and portfolio management. The core objective is to assess the likelihood that a borrower will default on their loan or credit obligations. Overall, credit risk classification using machine learning models to improve efficiency, accuracy, and realiability of credit risk assessment processes.

* Financial Information Regarding the Data 
The lending dataset involved multiple categories that went into determining an individuals loan status such as loan size, interest rate, borrower income, debt to income, number of accountts, derogatory marks, and total debt. The goal is to split the features into all of these categories and the labels column would be loan status.

## Stages of the machine learning process: 
* Split the data into training and testing datasets by using 'train_test_split'
* Create a Logistic Regression Model with the Orginal Data
* Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model
* Evaluate the model's performance by doing the following: calculate the accuracy score, generate a confusion matrix, and print the classification report 

* Predict a Logistic Regression Model with Resampled Training Data
* Apply Raondom Oversampling Techniques using 'RandomOverSampler'
* Create a new Logistic Regression Model using the oversampled data
* Evaulate the model's performance
  
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Accuracy: 0.99
  * Precision:
      Healthy Loans: 1.00 High Risk Loans: 0.87
  * Recall:
      Healthy Loans: 1.00 High Risk Loans: 0.95
    
* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Accuracy: 0.99
  * Precision:
      Healthy Loans: 0.99 High Risk Loans: 0.99
  * Recall:
      Healthy Loans: 0.99 High Risk Loands: 0.99 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. 
When the data is oversampled to have an equal amount of healthy loans and high risk loans, the model has an identical performance for predicting both classes. This demonstrates that with balanced data the model is equally effective at predicting both healthy loans (low default) and high risk (high default loans). However, with the original data since its split towards healthy loans the model more accurately predicted healthy loans compared to high risk loans. Overall, this indicates that dataset compositions can influence its predictive accuracy for different classes. 



