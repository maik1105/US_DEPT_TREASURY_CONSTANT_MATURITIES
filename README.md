# US Treasury Constant Maturities – LSTM Forecasting Project
This project explores the dynamics of U.S. interest rates using historical Federal Reserve time series data. 
It applies deep learning techniques—specifically Long Short-Term Memory (LSTM) networks—to model and forecast key economic indicators such as the 10-Year Treasury Yield.

## 📈 Project Overview

- **Objective**: Build a predictive model for U.S. Treasury yields using time series data and evaluate its performance.
- **Methodology**: 
  - Data preprocessing and feature engineering
  - Time series visualization and correlation analysis
  - LSTM model training and evaluation
- **Tools Used**: Python, Pandas, NumPy, Matplotlib, TensorFlow/Keras, Git

## 🔍 Data Source

- **Federal Reserve Economic Data (FRED)**: Time series data for U.S. Treasury constant maturities.
- Data includes yields across multiple durations (1M, 3M, 6M, 1Y, 2Y, 5Y, 10Y, 30Y).

## 🧠 Model Highlights

- LSTM architecture designed for sequential financial data
- Hyperparameter tuning for optimal forecasting accuracy
- Evaluation metrics include RMSE, MAE, and visual comparison of predicted vs. actual yields

## 📊 Results

- Forecasts show strong alignment with historical trends for longer maturities
- Model performance improves with feature selection and normalization
- Visualizations included for interpretability and validation
