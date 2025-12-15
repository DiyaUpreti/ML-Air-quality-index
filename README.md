# ML-Air-quality-index
Air Pollution (NOx) Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting Nitrogen Oxides (NOx) concentration using machine learning regression techniques. Air pollution is a major environmental and public health concern, and accurate prediction of pollutant levels can support environmental monitoring and decision-making.

The project applies predictive analytics to analyze air quality sensor data and compare multiple regression models to identify the most effective approach for NOx prediction.
🎯 Objectives

To analyze and preprocess real-world air quality data

To implement multiple machine learning regression models

To evaluate model performance using standard metrics

To compare models and identify the best-performing one

📂 Dataset

Name: Air Quality Dataset

Source: UCI Machine Learning Repository

Type: Multivariate environmental sensor data

Target Variable: NOx(GT)

Features: Gas sensor readings, temperature, humidity, and related environmental parameters

🛠️ Data Preprocessing

The following preprocessing steps were performed:

Removal of irrelevant columns (Date, Time, unnamed columns)

Handling missing values using mean imputation

Feature scaling using StandardScaler

Splitting data into training and testing sets (80:20 ratio)

🤖 Machine Learning Models Used

The project implements and compares the following regression models:

Linear Regression

K-Nearest Neighbors (KNN) Regression

Decision Tree Regression

Random Forest Regression

📊 Model Evaluation Metrics

Model performance was evaluated using:

R² Score – to measure explained variance

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Visual comparisons were made using tables and bar charts.

🏆 Results & Model Comparison

Among all the models tested, Random Forest Regression achieved the best performance with:

Higher R² Score

Lower RMSE and MSE

Better handling of nonlinear relationships

This demonstrates the effectiveness of ensemble learning techniques for environmental prediction tasks.

📈 Visualizations

Model comparison bar charts

Actual vs Predicted NOx values

Residual error distribution

Feature importance (for tree-based models)

🚀 Technologies & Libraries Used

Python

NumPy

Pandas

Matplotlib

Scikit-learn

📌 Conclusion

This project highlights the application of machine learning regression techniques in air pollution prediction. The comparative analysis shows that advanced ensemble models outperform basic regression approaches, making them suitable for real-world environmental monitoring systems.

