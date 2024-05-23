# Steel melting temperature prediction
To optimize production costs, thed metallurgical plant decided to reduce energy consumption at the steel processing stage. To do this, the plant needs to control the temperature of the alloy. The task is to build a model that will predict it.
Data was collected from various sources, therefore, this project includes extensive feature research followed by feature engineering. Features are merged in one dataset, checked for correlation and selected for models.
The data is divided into features and target with data mixing.
Several models were trained with selection of parameters. The importance of the features was analyzed: the most important were “temperature_start”, “total_power”, “Bulk_12”, “Gas1”, “Wire_1”, “Wire 4”. By adjusting their values during production, you can optimize the process and reduce energy costs.
The effectiveness of the model was assessed on a test sample. The best model turned out to be XGBRegressor with a mae value on the test sample of 5.9
## Required Libraries
The project requires the following Python libraries:

pandas,
numpy,
scikit-learn,
xgboost,
matplotlib,
seaborn

## Analysis Process
Data Loading: Load the dataset and preprocess it by handling missing values, outliers, and unnecessary columns.  
Feature Engineering: Prepare features and compile a single table with all the data for the model.  
Model Training: Train several models with different hyperparameters and evaluate their performance.  
Feature Importance: Analyze the importance of features, focusing on those that significantly impact the model's predictions.  
Model Evaluation: Assess the effectiveness of the models on a test sample.  

## Conclusion
The project successfully built a predictive model to forecast the temperature of the steel alloy during the melting process. The XGBRegressor model showed the best performance, with an MAE of 5.9. By adjusting the values of the most important features during production, the metallurgical plant can optimize the process and reduce energy costs.
