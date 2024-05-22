## Taxi Order Forecasting
# Project Overview
The Clear Taxi company needs to predict the number of taxi orders at airports for the next hour to attract more drivers during peak periods. 
The goal is to build a model that can make accurate predictions, with an RMSE (Root Mean Square Error) metric value on the test sample of no more than 48.

# Introduction
Clear Taxi has collected historical data on taxi orders at airports. Predicting the number of taxi orders for the next hour will help the company manage driver availability more effectively during peak periods.

# Problem Statement
The task is to predict the number of taxi orders for the next hour using historical data. The target metric is RMSE, with a requirement that it should not exceed 48 on the test sample. The steps to achieve this include:

* Loading and resampling the data.
* Analyzing the data.
* Training various models with different hyperparameters.
* Evaluating the models on a test sample.
* Data Description
The dataset is contained in the file taxi.csv and includes:

num_orders: The number of taxi orders.
The data needs to be resampled on an hourly basis for the analysis and modeling process.

# Installation
System Requirements
Operating System: Windows, macOS, or Linux
Python Version: 3.8 or higher
# Required Libraries
The project requires the following Python libraries:

pandas  
numpy  
scikit- learn  
lightgbm  
catboost  
matplotlib  
seaborn  


# Results
The analysis yielded the following results:

Linear Regression: [RMSE on test set]  
RandomForestRegressor: [RMSE on test set]  
LightGBM:  
RMSE on training set: 25.497  
RMSE on test set: 44.9143  
CatBoost: [RMSE on test set]    
The LightGBM model achieved the lowest RMSE on the test set, meeting the project's requirements.

# Conclusion
Data on taxi orders at airports was analyzed, and models were developed to predict the number of orders for the next hour. The LightGBM model demonstrated the best performance with an RMSE of 44.9143 on the test set, which is below the required threshold of 48.
