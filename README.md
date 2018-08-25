# Mobile-Fraud-Detection
BIA670 Risk Management Course Project

## Problem 
Use supervised machine learning methods(SML) to forecast which transactions are frauds.

## Motivation
Mobile money transactions becomes increasingly important in people's daily life. Meanwhile, fraud mobile transactions becomes a big problem for the related financial agents. Therefore, applying a useful method for mobile transactions fraud detection based on the given data is the objective of this project.

## Objective
* Perform EDA to see the distribution of fraud transactions in each transaction type.
* Select features and preprocess data based on the results of EDA, Random Forest and Pearson Correlation.
* Under-sampling creates union bootstrap sample used for Stacking model.
* Employ two-level stacking model to combine SML predictions.
* Use SMOTE to deal with imbalanced data and combine the classifier of logistic regression.
* Compare the prediction redults on the raw imbalanced dataset in three situations.

## Dataset
The dataset made available on [Kaggle](https://www.kaggle.com/ntnu-testimon/paysim1 ) contains mobile money transactions based on a sample of real transactions extracted from one month of financial logs from a mobile money service implemented in an African country. The original logs were provided by a multinational company, who is the provider of the mobile financial service which is currently running in more than 14 countries all around the world.
