# Detecting Toxic Comments for an Online Shop
## Project Overview
The Wikishop online store is launching a new service that allows users to edit and add product descriptions, similar to wiki communities. To maintain a positive environment, the store needs a tool to detect toxic comments and send them for moderation. The objective of this project is to train a model to classify comments into positive and negative categories, achieving an F1 score of at least 0.75.

The task is to build a model that can accurately classify comments into positive and negative categories. The goal is to achieve an F1 score of at least 0.75 on the test set. The steps to achieve this include:

* Downloading and preparing the data.
* Training various models.
* Evaluating the models and selecting the best one.

## Required Libraries
The project requires the following Python libraries:  

pandas  
numpy  
scikit-learn  
catboost  
nltk  

## Analysis Process
* Data Loading: Load the dataset and preprocess it by removing unnecessary columns and analyzing comment lengths.
* Text Preprocessing: Clean, lemmatize, and vectorize the text data using the Tfidf method.
* Model Training: Train several models, including Logistic Regression, Decision Tree, and CatBoost, with various hyperparameters.
* Model Evaluation: Evaluate the models on a test sample and compare their F1 scores to select the best model.

## Results
The analysis identified the Logistic Regression model as the best performer with the following results:

* F1 Score on Training Set: .754298
* F1 Score on Test Set: 0.763  
Other models, including Decision Tree and CatBoost, were also evaluated, but the Logistic Regression model achieved the highest F1 score on the test set.
