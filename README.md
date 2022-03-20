# Credit Risk Analysis

## Overview of the Analysis

This notebook performs a credit risk analysis by predicting whether or not a loan is determined as risky or not based on particular data about the potential borrower.

* In order to correctly determine a risky loan, machine learning techniques will be used. The data used by the machine learning algorithm contains information about borrower, including: loan size, interest rate, borrower income, debt to income ratio, total debt, among some others.
* The analysis will first determine a model to use (in this case, Logistic Regression). Second, the data obtained about a potential borrower will be used to fit the data, that is adjusting the model to match patterns found in the dataset. Third will be to predict which loans are risky and which ones are not using a dataset different from the one used to train the algorithm.
* Two main functions are used for analysis. One is Logistic Regression, and the other function is RandomOverSampler to create a resampled dataset for the machine learning algorithm.

<br>

## Results

The results of the credit risk analysis using two models of logistic regression. The results will show how accurately the model predicted risky loans:

* Logistic Regression Model 1 (Non-resampled Data):
  * Accuracy: 95.2%
  * Precision: 85%
  * Recall: 91%

<br>

* Logistic Regression Model 2 (Resampled Data):
  * Accuracy: 99.4%
  * Precision: 84%
  * Recall: 99%

<br>

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The resampled logistic regression model performs better than the non-resampled model as it better predicted which loans are risky and which ones are not.
* For this analysis, the goal was to improve the accuracy for predicting risky loans properly.

While both models performed similarly, the resampled logistic regression model is the preferred method for analyzing credit risk. Although precision seems to be lower using the non-resampled model, the accuracy and recall values are much higher for the resampled model.