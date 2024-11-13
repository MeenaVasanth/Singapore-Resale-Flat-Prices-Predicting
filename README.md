# Singapore-Resale-Flat-Prices-Predicting
# Problem Statement:
The objective of this project is to develop a machine learning model and deploy it
as a user-friendly web application that predicts the resale prices of flats in
Singapore. This predictive model will be based on historical data of resale flat
transactions, and it aims to assist both potential buyers and sellers in estimating
the resale value of a flat.
# Technology and Skills Takeaway
Python: Programming language used for data preprocessing, model training, and deployment.
Pandas & Numpy: Used for data manipulation and handling numerical operations.
Scikit-Learn: Library used for building and evaluating machine learning models.
Streamlit: Framework used for building the interactive dashboard for the application.
Pickle: Used for model serialization.
Render: Platform used for deploying the Streamlit application.
# Overview
# Data Collection:
The dataset, sourced from official HDB publications, covers resale flat data from 1990 to the present.
# Data Preprocessing: 
Cleaned the raw data by handling missing values, correcting inconsistencies, and performing feature engineering (e.g., deriving property age and lease duration, log transformations for skewed features).
# Outlier Handling & Skewness Correction: 
Outliers were identified and managed; log transformations corrected skewed distributions in variables like floor area and price per square meter.
# Categorical Encoding:
Categorical features such as flat type, flat model, and town were encoded into numerical values using Label Encoding.
# Model Selection & Training:
Evaluated multiple models (Linear Regression, Random Forest, Decision Tree), selecting the Decision Tree Regressor for its superior performance based on R-squared and Mean Squared Error.
# Model Deployment: 
The trained model was serialized using pickle, and an interactive Streamlit dashboard was deployed on Render, allowing users to make resale price predictions based on selected features..
