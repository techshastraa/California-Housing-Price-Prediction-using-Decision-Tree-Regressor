# 🏡 California Housing Price Prediction using Decision Tree Regressor

This project demonstrates the use of a **Decision Tree Regression model** to predict housing prices based on the **California Housing dataset**. It includes both a baseline model and an optimized version using **GridSearchCV** for hyperparameter tuning.

## 📌 Features

- Uses `fetch_california_housing()` from `sklearn.datasets`
- Trains a `DecisionTreeRegressor` model
- Evaluates using:
  - Mean Squared Error (MSE) : 0.43
  - R² Score : 0.66
- Performs GridSearchCV on:
  - `max_depth` 1 to 10
  - `min_samples_split` 5
  - `min_samples_leaf` auto


