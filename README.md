# Advance_Time_Series![diagram](https://github.com/user-attachments/assets/47d5d95c-f83a-4b3b-995f-2247bdf00311)
# 📈 Multi-Model Stock Forecasting (ARIMA, Prophet, LSTM)

This project performs stock price forecasting using three distinct models — **ARIMA**, **Prophet**, and **LSTM** — to identify the best-performing method for each stock based on RMSE (Root Mean Squared Error).

## 🚀 Features

- Download historical data from Yahoo Finance (`yfinance`)
- Train ARIMA (statistical), Prophet (additive), and LSTM (deep learning) models
- Evaluate and compare performance using RMSE
- Auto-select the best model per stock
- Save line charts comparing actual vs. predicted prices

## 📊 Models Used

- **ARIMA**: Autoregressive Integrated Moving Average from `statsmodels`
- **Prophet**: Additive time series forecasting from Meta/Facebook
- **LSTM**: Deep learning model using TensorFlow/Keras

## 🛠️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
