This project focuses on building a Predictive Maintenance system using Machine Learning techniques and the Microsoft Azure Predictive Maintenance Dataset. The dataset contains machine telemetry sensor readings such as voltage, rotation, pressure, and vibration collected hourly from multiple industrial machines.

The project aims to analyze machine behavior and identify patterns related to machine failures. Different data preprocessing and machine learning techniques were applied to clean the data, handle missing values, balance the dataset using SMOTE, and build predictive models.

Since the dataset contains time-based telemetry data, a time-series approach was used for train-test splitting to make the prediction process more realistic and avoid data leakage. Multiple classification algorithms were tested, including Logistic Regression, Decision Tree, and Random Forest. Random Forest was selected as the best-performing model based on evaluation metrics.

This project demonstrates how Machine Learning can be applied in industrial environments to predict failures before they occur, helping reduce downtime, maintenance cost, and operational risk.

The dataset used in this project is the Microsoft Azure Predictive Maintenance Dataset. It contains industrial machine telemetry data collected from 100 machines between January 2015 and January 2016 at one-hour intervals.

Data Source: https://www.kaggle.com/datasets/arnabbiswas1/microsoft-azure-predictive-maintenance
