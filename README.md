# Credit-Card-Fraud-Detection

## Overview 
Credit card fraud detection is crucial to safegaurd financial transaction. The main goal is to the significant factors and hidden insights about credit card fradulant activities from past data.  ML models will be used to predicts if a credit card transaction is fraudulent or not. Different ML models and Snap ML will be used for modelling and predicting , the best model will be selected based on time and ROC score.

## Business Understanding 

Credit card fraud detection is vital for financial organizations. It safeguards transactions, reduces losses, and maintains trust. As online transactions rise, proactive fraud prevention becomes crucial to protect revenue and enhance customer experience. So using machine learning for detection will increase the accuracy , save alot of manual work and will help in processing huge data logs within less time.

## Modeling and Evaluation 

* Machine Learning algorithms used were Logistic Regression , Support Vector Machine and Decision tree.
* same algorithms were implemented using Snap ML library .
Snap ML is an advanced IBM library for machine learning modeling, delivers efficient CPU/GPU implementations of linear and tree-based models. Beyond accelerating existing ML algorithms with system awareness, Snap ML introduces innovative ML algorithms known for their exceptional accuracy. 
* Evaluation metric used is ROC score.

## Dataset
Real dataset was used to train each of these models. The dataset includes information about transactions made by credit cards in September 2013 by European cardholders.
Data Source : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Conclusion 
The SVM model using Snap ML outperformed the other models . 
