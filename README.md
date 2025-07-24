# 📈 Tesla Stock Price Forecasting using ARIMA & SARIMA

## 📌 Project Overview
This project focuses on forecasting Tesla (TSLA) stock prices using time series models: ARIMA and SARIMA. The goal is to evaluate which model performs better in predicting stock trends based on historical data.

## 📂 Dataset
- **Source**: Kaggle
- **Data**: Historical Tesla stock price data (Open, Close, High, Low, Volume, etc.)

## 🧠 Methods Used
- **Exploratory Data Analysis**
- **Time Series Decomposition**
- **Stationarity Check (ADF Test)**
- **ACF and PACF Plots**
- **ARIMA and SARIMA Modeling**
- **Model Tuning**
- **Forecasting**
- **Model Evaluation (RMSE, MAE, MAPE)**

## 📊 Evaluation Metrics

| Metric | SARIMA | ARIMA |
|--------|--------|--------|
| RMSE   | 106.44 | 91.24  |
| MAE    | 93.46  | 80.86  |
| MAPE   | 11.24% | 9.66%  |

## 📌 Insights
- The **ARIMA model** outperformed SARIMA in all evaluation metrics.
- ARIMA showed lower error rates (RMSE, MAE, MAPE), indicating better forecast accuracy for Tesla stock prices.
- SARIMA, though seasonal, didn't capture strong seasonality in the TSLA data compared to ARIMA's efficiency.

## 📎 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- statsmodels, pmdarima
