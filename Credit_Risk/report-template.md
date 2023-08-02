# Module 12 Report

## Overview of the Analysis


* Purpose of the analysis
  * Use Logistic Regression to train and evaluate a model based on loan risk. Dataset of historical lending activity from a peer-to-peer lending services company to be used to build a model that can identify the creditworthiness of borrowers.
* As part of the machine learning process, following steps were followed:
  * Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
  * Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
  * Split the data into training and testing datasets by using train_test_split.
  * Fit a logistic regression model by using the training data (X_train and y_train).
  * Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
  * Evaluate the model’s performance by doing the following:
    * Generate a confusion matrix.
    * Print the classification report.


## Results

* Accuracy Scoere - 0.99
* Precision Score(Weighted Avg) -  0.99
* Recall Score(Weighted Avg) - 0.99


## Summary

* Accuracy of the model at 99.2 % is very high. Precision and recall are 100% for healthy loans and 87%,89% resp.  for high risk loan. So the model is able to predict healthy loans very well but the high risk loans a little less successfully. 
* However with an overall score of 99% for accuracy,precision and recall, the model does a very good job of predicting the loans.
* Hence this model should be used by the companies but with the understandint that the prediction  of the at-risk loans is not as accurate as that of th healthy loans.
