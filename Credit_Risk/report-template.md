# Module 12 Report Template

## Overview of the Analysis

The purpose of the analysis is to build a logistic regression model that can identify the creditworthiness of borrowers

This is a dataset of historical lending activity from a peer-to-peer lending services company. 
This analysis is to predict the loan status which indicate the loan is healthy or at risk.

In this analysis, first of all, I splited the data inro training and testing sets. Then, create a logistic regression model with the original data. Next, Predict a logistic regression model with resampled training data. Finally, I evaluate the performance of the model.

In the first logistic model, I used the LogisticRegression module from SKLearn to create the model.
In the second model, I used the RandomOverSampler module from the imbalanced-learn library to resample the data.

## Results

* Machine Learning Model 1:
  The balanced accuracy score is 0.9520479254722232
  Precision: 100% on healthy loan and 85% on high-isk loan
  Recall: 99% on healthy loan and 91% on high-risk loan


* Machine Learning Model 2:
  The balanced accuracy score is 0.9936781215845847
  Precision: 100% on healthy loan and 84 on high-isk loan
  Recall: 99% on healthy loan and 99 on high-risk loan

## Summary

The second logistic regression model with resampled training data performed better than the first logistic regression model since it had a greater balance accuracy score, greater recall.

