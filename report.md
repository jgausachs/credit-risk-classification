# Module 12 Report

## Overview of the Analysis

We analysed a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The credit risk of borrowers was presented against the following variables:

* loan size
* interest rate of loan
* borrower income
* debt to income ratio
* number of accounts held
* derogatory marks on borrower file
* total debt

Two machine learning models were trained on a dataset of 77,536 loan application and used predict credit risk of borrowers. 

Initially, a Logistic Regression Model (Machine Learning Model 1) was used. The analysis was then improved by developing Resampled Training Data and applying it to a new Logistic Regression Model (Machine Learning Model 2).

## Results

Key results (balanced accuracy score, and precision and recall scores) of the machine learning models are as follows:

* Machine Learning Model 1:
  * Balanced accuracy score: 0.9520479254722232
  * Precision score: 0.99
  * Recall score: 0.99

* Machine Learning Model 2:
  * Balanced accuracy score: 0.9936781215845847
  * Precision score: 0.99
  * Recall score: 0.99

## Summary

Model 1 achieves better results predicting healty loans than high-risk loans. It predicts the healthy loans with 99% accuracy and the high-risk loans with 91% accuracy.

Model 2 (which uses Resampled Training Data) chieves similar results predicting healty loans and high-risk loans. It predicts both the healthy loans and the high-risk loans with 99% accuracy.

We recommend the use of Model 2, as it achieves better results predicting both healthy loans and high-risk loans.

