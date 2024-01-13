# food-delivery-time-prediction

# Problem Statement:

In the fast-paced world of food delivery, time is of the essence. The ability to accurately predict delivery times is not just a convenience but a game-changer for both customers and businesses and for this problem i have devloped this ml model.

# Objective:

Purpose of this Project to predict delivery time accurately based on the input parameters like Delivery_person_Ratings, Restaurant_latitude, Restaurant_longitude,Delivery_location_latitude,Delivery_location_longitude,Order_Date, Time_Orderd,Time_Order_picked, Weather_conditions, Road_traffic_density,
Vehicle_condition, Type_of_order, Type_of_vehicle,multiple_deliveries,Festival,City etc. 

Each row in the data provides relavant information about the delivery. Throughout this Project i have followed the whole life cycle of a Data Science Project as:
EDA(Exploring Data and Understanding features doing univariate analysis,Bivariate analysis,Finding Distribution) and Data Cleaning(Finding Types of Features,Duplicate values,Missing Values,Outlier Detection)
Feature Engineering((Imputting Missing Values,Outlier,handlingImbalanced)) and Feature Selection ,Feature Scaling
Model Selection
Model Building
Model HyperParameter Tuning
Model Evaluation(Testing)


# Tools and Technologies Used :

Python,Machine Learning,Sklearn,Pandas,Matplotlib,Seaborn,Numpy

# Data Collection:

I have gathered dataset from open government data website for this project.

# EDA:

Perform eda on dataset to derive some conclusion and insights which could further in model building.

# Feature Engineering:

Impute Missing values,handle ouliers,removing duplicates values.

# Feature Selection:

Perform feature selection using correlation matrix and tried to know which feature is impacting much to my target variable.

# Model selection and building:

used various machine learning algorithms(SVR ,Decision tree Regressor,Random forest Regressor,XGBoost Regressor) and tried to know which best suite on my dataset.


# Model Tuning
perform hyperparameter tuning on Decision tree Regressor and achieved accuracy 91%.

# Model Tesing:

perform model testing on unseen data.

# Model Deployment:
save the model and loaded it Pycharm to delpoy it.
