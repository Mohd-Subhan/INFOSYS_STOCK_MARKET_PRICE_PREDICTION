INFOSYS Stock Price Prediction
Project Overview

This project focuses on predicting the next day’s closing price of INFOSYS stock using historical stock market data and machine learning techniques.

The project follows a complete data science workflow including data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

Objective

Predict next day’s closing price using today’s stock data

Understand stock price trends using EDA

Compare different regression models

Identify the best-performing model

Dataset

The dataset contains daily stock prices of INFOSYS with the following columns:

Date

Open

High

Low

Close

Adj Close

Volume

Data Preprocessing

Converted Date column to datetime

Sorted data in chronological order

Handled missing values

Created next-day target column

Split data into train and test sets

Applied feature scaling where required

Exploratory Data Analysis (EDA)

Closing price trend over time

Distribution of closing prices

Correlation between features and target

Visual comparison of actual vs predicted prices

Machine Learning Models Used

Linear Regression

K-Nearest Neighbors (KNN) Regressor

Decision Tree Regressor

Random Forest Regressor

Model Evaluation

Models were evaluated using:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score

Best Model

Linear Regression performed best in predicting the next day’s closing price.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

Author

Mohd Subhan
B.Tech Computer Science | Data Science Minor
Aspiring Data Scientist & Machine Learning Enthusias
