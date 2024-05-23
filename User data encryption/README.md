# Protection of Clients' Personal Data
## Project Overview
The goal of this project is to develop a method for transforming data to protect the personal information of clients of the insurance company "Though the Flood." 
The method should ensure that it is difficult to recover personal information from the transformed data while maintaining the quality of machine learning models.

## Introduction
In the insurance industry, protecting clients' personal data is crucial. This project involves developing and justifying a data transformation method that safeguards personal information while ensuring the quality of machine learning models is not compromised.

## Problem Statement
The task is to create a data transformation algorithm that makes it difficult to recover personal information from the transformed data. The transformation should not deteriorate the quality of machine learning models.
Specifically, we aim to prove that the quality of linear regression models remains unchanged after data transformation.

## Data Description
The dataset includes personal information of clients from the insurance company "Though the Flood." The features are transformed using matrix multiplication, ensuring the data's security without affecting model performance.

## Required Libraries
The project requires the following Python libraries:
pandas  
numpy  
scikit-learn  

# Algorithm

The features are multiplied by an invertible matrix to protect the data. Here are the key points:

Quality of Linear Regression: The quality of linear regression will not change due to the properties of matrix multiplication.  
Properties of Matrices:  
Multiplying by an invertible matrix does not affect predictions.  
The transformed feature matrix maintains the same linear relationships as the original matrix. 
Transformation Algorithm  
Create an Invertible Matrix:  
Generate a random matrix.  
Ensure its determinant is non-zero to confirm it is invertible.  
Check Dimensions:  
Ensure the dimensions of the matrices allow for multiplication.  
Multiply Feature Matrix:  
Multiply the feature matrix by the invertible matrix.  
# Model Evaluation: 
Evaluate model quality on both the original and transformed data.    
Compare metrics to ensure encryption does not affect model performance.  
Algorithm Check  
The algorithm was validated by comparing model performance on the original and transformed data. The results showed a negligible discrepancy in metrics, confirming that the transformation maintains model quality.   

# Conclusion
Effectiveness: The algorithm effectively protects client data by making it difficult to recover personal information from the transformed data.  
Model Quality: The transformation does not deteriorate the quality of machine learning models, specifically linear regression.  
Recommendation: This transformation method is recommended for protecting personal data in machine learning applications.  
