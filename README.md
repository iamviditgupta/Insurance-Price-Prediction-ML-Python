# Insurance-Price-Prediction-ML-Python

# Overview
Health insurance cost prediction is a crucial task in the healthcare industry, aiding individuals and organizations in estimating future healthcare expenses. This project aims to predict health insurance costs based on factors such as age, gender, BMI, number of children, smoking status, and location using machine learning algorithms.

# Dataset
The dataset contains information about individuals and families, including variables such as age, gender, BMI, number of children, smoking status, residential region, and medical costs. The target variable is the "charges" column, representing individual medical costs billed by health insurance.

# Methodology
**Data Preprocessing:** Handled missing values, encoded categorical columns, and split the dataset into training and testing sets.
**Model Development:** Developed and evaluated several machine learning models (Linear Regression, Decision Tree Regression, Random Forest Regressor, KNN Regressor, Support Vector Regressor, and XG Boost Regressor) to predict health insurance costs.
**Model Deployment:** Trained the Random Forest Regressor model on the entire dataset and saved it for future use.

# GUI Interface
The project includes a graphical user interface (GUI) using Tkinter, allowing users to input their information and get a predicted health insurance cost based on the trained machine learning model.
