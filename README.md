# Stock Price Prediction Using LSTM

An LSTM (Long Short-Term Memory) neural network model for predicting Apple Inc. (AAPL) stock closing prices using historical time series data.

## Overview

Stock market prediction is a central challenge in quantitative finance. This project uses an LSTM-based deep learning model trained on historical OHLCV data enriched with technical indicators to predict the next-day closing price of AAPL stock.

Traditional statistical models like ARIMA often struggle to capture nonlinear dependencies in financial data. LSTMs, designed for sequential data and long-term dependencies, offer stronger performance for time series forecasting.

## Project Structure

The notebook follows a structured pipeline:

1. **Problem Statement** - Defining the prediction task and its significance
2. **Data Collection** - Fetching historical data from Yahoo Finance via `yfinance`
3. **Data Exploration** - Visualizing trends, distributions, and correlations
4. **Data Preprocessing** - Cleaning, scaling, and preparing data for modelling
5. **Feature Extraction** - Engineering technical indicators from raw price data
6. **Model Training** - Building and training the LSTM network
7. **Results** - Evaluating model performance with metrics (RMSE, MAE, R²)
8. **Conclusion** - Summary of findings

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- yfinance

## Getting Started

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow yfinance xgboost
jupyter notebook
```

Open `Theo_|_Method_Prediction.ipynb` and run all cells.

## License

This project is for educational purposes.
