# Gold Price Forecasting using Machine Learning

## Overview
This project focuses on predicting gold prices using machine learning techniques with time-series feature engineering.

## Key Features
- Data preprocessing and cleaning
- Time-series transformation using date index
- Lag feature creation (T-1) to avoid data leakage
- Model training using Linear Regression and Random Forest
- Model evaluation using MAE, RMSE, and R²

## Models Used
- Linear Regression
- Random Forest Regressor

## Tools & Libraries
- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib

## Results
The models were evaluated on unseen data and predictions were visualized to compare actual vs predicted gold prices.

## Key Learning
- Avoiding data leakage in time-series problems
- Importance of lag features
- Comparing different ML models for forecasting

## Sample Output

### Linear Regression Prediction
![Linear Regression](gold-price-forecasting/images/Linear Regression Prediction.png)

### Random Forest Prediction
![Random Forest](gold-price-forecasting/images/Random Forest Prediction.png)
