# Car-Price-Prediction-Model

﻿This project aims to predict the selling prices of cars using various regression techniques. The model is designed as a mini-project for practice and showcases the application of machine learning in predicting real-world values based on historical data.

**Dataset**
The dataset used for this project contains information about 301 cars, including features such as:
Car Name
Year of Manufacture
Selling Price
Present Price
Kms Driven
Fuel Type (Petrol, Diesel, CNG)
Seller Type (Dealer, Individual)
Transmission (Manual, Automatic)
Owner Count

**Data Processing**
The data undergoes several preprocessing steps:
Loading the Data: The dataset is imported from a CSV file.
Handling Missing Values: A check confirms that there are no missing values in the dataset.
Encoding Categorical Variables: Categorical features such as Fuel Type, Seller Type, and Transmission are converted into numerical values for model compatibility.
Feature Selection: The features are selected by removing non-predictive columns like Car Name and the target variable Selling Price.

**Model Training**
The dataset is split into training and testing sets, with 90% of the data used for training. Various regression models are implemented to evaluate their performance in predicting car prices:
1. Linear Regression
2. Lasso Regression
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Decision Tree Regressor
   
**Model Evaluation**
Each model's performance is assessed using the R² score, which indicates how well the model explains the variability of the target variable:
Higher R² scores signify better predictive accuracy.
Visualizations of actual vs predicted prices are generated to provide insights into model performance.

**Conclusion**
The Random Forest and Gradient Boosting models exhibit superior performance in predicting car prices compared to other models. The Decision Tree model shows excellent training performance but indicates potential overfitting due to a significant drop in testing accuracy.
