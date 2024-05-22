# Steel melting temperature prediction
To optimize production costs, thed metallurgical plant decided to reduce energy consumption at the steel processing stage. To do this, the plant needs to control the temperature of the alloy. The task is to build a model that will predict it.
Data was collected from various sources, therefore, this project includes extensive feature research followed by feature engineering. 
The data is divided into features and target with data mixing.
Several models were trained with selection of parameters. The importance of the features was analyzed: the most important were “temperature_start”, “total_power”, “Bulk_12”, “Gas1”, “Wire_1”, “Wire 4”. By adjusting their values during production, you can optimize the process and reduce energy costs.
The effectiveness of the model was assessed on a test sample. The best model turned out to be XGBRegressor with a mae value on the test sample of 5.9
