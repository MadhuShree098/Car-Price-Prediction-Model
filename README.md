# Car-Price-Prediction-Model

﻿This mission aims to expect the promoting fees of automobiles the use of various regression techniques. The version is designed as a mini-assignment for exercise and showcases the software of machine gaining knowledge of in predicting actual-global values based totally on historic data.
Dataset
The dataset used for this undertaking includes records about 301 motors, along with features which includes:
Car Name
Year of Manufacture
Selling Price
Present Price
Kms Driven
Fuel Type (Petrol, Diesel, CNG)
Seller Type (Dealer, Individual)
Transmission (Manual, Automatic)
Owner Count
Data Processing
The records undergoes numerous preprocessing steps:
Loading the Data: The dataset is imported from a CSV document.
Handling Missing Values: A test confirms that there are no missing values inside the dataset.
Encoding Categorical Variables: Categorical capabilities including Fuel Type, Seller Type, and Transmission are converted into numerical values for model compatibility.
Feature Selection: The capabilities are selected by using eliminating non-predictive columns like Car Name and the target variable Selling Price.
Model Training
The dataset is break up into schooling and checking out units, with ninety% of the information used for education. Various regression fashions are implemented to assess their overall performance in predicting car prices:
Linear Regression
Lasso Regression
Random Forest Regressor
Gradient Boosting Regressor
Decision Tree Regressor
Model Evaluation
Each version's performance is classed the usage of the R² rating, which indicates how nicely the version explains the range of the goal variable:
Higher R² scores symbolize higher predictive accuracy.
Visualizations of real vs expected charges are generated to offer insights into version performance.
Conclusion
The Random Forest and Gradient Boosting fashions showcase advanced overall performance in predicting car costs in comparison to other fashions. The Decision Tree model shows excellent education overall performance but suggests ability overfitting due to a huge drop in testing accuracy.
