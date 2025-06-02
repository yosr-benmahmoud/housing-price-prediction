# Housing Price Prediction
# 🏡 Housing Price Prediction - California Dataset

This project aims to build a machine learning model to predict median housing prices in California districts, based on features such as population, median income, and location.

## 📌 Overview

- Data Cleaning & Preprocessing
- Feature Engineering
- Pipelines for Numerical and Categorical attributes
- Model Training: Linear Regression, Decision Tree, Grid Search CV
- Performance Evaluation (RMSE, Cross-Validation)

## 🧠 Motivation

Predicting housing prices is crucial for real estate companies, investors, and policy makers. This project demonstrates an end-to-end regression pipeline using Scikit-Learn.

## 📂 Dataset

- **Source**: [California Housing from StatLib](https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html)
- Contains features such as:
  - Median income
  - Number of rooms
  - Population
  - Latitude / Longitude

## 📊 Models Used

- Linear Regression
- Decision Tree Regressor
- GridSearchCV for hyperparameter tuning

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy, Matplotlib
- Scikit-learn

## 🚀 Final Performance

- **Best RMSE (Decision Tree + Grid Search)**: ~60,035
- Compared to baseline Linear Regression: ~68,628



