Employee Turnover Analysis and Prediction)

Task Overview: This project is divided into three main parts: data analysis, clustering, and predictive modeling, focusing on employee turnover. The key objectives are to 
perform data analysis, cluster employees, predict total turnover for a given year, and classify employees likely to quit.

Part 1: Data Analysis: This part involves answering several questions about the dataset, understanding key patterns, and preparing the data for modeling.

Part 2: Data Science Tasks
Clustering Employees with K-Means

Objective: Cluster employees based on the following features: age length_of_service department job_title For each year: Perform clustering for the year 2025 and repeat the 
process for previous years. Key Question: Does the same employee remain in the same cluster every year, or do they switch clusters over time?

Regression Time Series Task: Predict Total Employee Turnover Objective: Build a regression model to predict the total employee turnover for a given year. Target: Total 
employee turnover (annual). Models Used: Linear Regression RandomForestRegressor ExtraTreeRegressor

Binary Classification Task: Predict Employee Churn Objective: Adapt the regression model to predict individual employee churn, determining which employees are most likely 
to quit. Target: Employee turnover (binary classification: quit vs. not quit). Models Used: Logistic Regression XGBoost

Preprocessing Steps: Before building the models, the following preprocessing steps were applied:

Handling missing values Encoding categorical variables Dealing with data imbalance and skewness Rescaling features
