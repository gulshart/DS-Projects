# Customer Churn Prediction for Beta Bank #

## Project Overview ##
This project aims to predict whether a client will leave Beta Bank in the near future using historical data on customer behavior and contract termination.
The goal is to build a machine learning model with a high F1-score, targeting an F1-measure of at least 0.59.
Additionally, the project involves measuring the AUC-ROC and comparing its value with the F1 measure.

The best result F1-0.591 measure was achieved when training the Random Forest model on an enlarged sample with hyperparameters 
number of trees -122, depth -14. The AUC-ROC metric was 0.84, which indicates a high probability of being included in the classes.
