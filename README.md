# carpriceanalysis
using ml model we find which is the best suitable price 

Problem Statement: Predict the selling price of used cars based on various features such as car age, fuel type, transmission type, and previous ownership history. The goal is to build a regression model that accurately estimates car prices to assist buyers and sellers in making informed decisions.


The notebook analyzes car prices using machine learning techniques. It starts by loading a dataset from 'car data.csv' and performing data preprocessing, including dropping irrelevant columns, creating a Car_Age feature, and applying transformations like PowerTransformer and OneHotEncoder. The dataset is then split into training and testing sets. Several regression models, including LinearRegression, BayesianRidge, RandomForestRegressor, GradientBoostingRegressor, AdaBoostRegressor, and XGBoost, are trained using a pipeline with column transformations. The models are evaluated using metrics like mean_absolute_error, mean_squared_error, and r2_score, with predictions made to estimate car prices. Data visualizations, including distribution plots and feature importance graphs, help analyze patterns and model performance.
