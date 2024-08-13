# Mobile plan choice #

## Project Overview ##
This project aims to build a machine learning model to recommend the appropriate data plan ("smart" or "ultra") based on the behavior of customers who have already switched to these plans. 
The primary goal is to achieve the highest possible accuracy, with a minimum threshold of 75% accuracy on the test sample.

## Project Description ##
The objective is to classify customers into two data plans: "smart" and "ultra". The project involves:

* Studying the source data.
* Splitting the data into training, validation, and test sets.
* Applying three machine learning models: Decision Tree, Random Forest, and Logistic Regression.
* Identifying the model with the highest accuracy.
* Evaluating the best model on a test sample.
* Data Description
  
The dataset includes features related to customer behavior, such as:

* Number and duration of calls
* Internet traffic used
* Number of SMS messages
* Whether the customer switched to the ultra tariff (target variable)
* Installation

### Required Libraries ###
 The project requires the following Python libraries: ###

pandas
numpy
scikit-learn
matplotlib
seaborn

### Model Evaluation
The performance of the models is evaluated primarily using accuracy. The project compares the accuracy of three models: Decision Tree, Random Forest, and Logistic Regression. The best-performing model is selected based on its accuracy on the validation set and further evaluated on the test set.

## Results ##
Three models were tested:

Decision Tree Classifier,
Random Forest Classifier,
Logistic Regression.
The Random Forest Classifier model achieved the highest accuracy:

Validation Accuracy: 0.8025,
Test Accuracy: 0.7978,
This indicates a slight overfitting but meets the project requirement of 75% accuracy.
