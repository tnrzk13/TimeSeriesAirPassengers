# AirPassengers Time Series Forecasting

This project demonstrates understanding in time series analysis and forecasting. The goal is to analyze and predict the number of airline passengers in the future of at least 12 months.

## Table of Contents

1. Define the Problem
2. Collect and clean the data
3. Explore and visualize the data
4. Test for stationarity
5. Make the time series stationary
   5.1 - Decomposition
   5.2 - Differencing
6. Create the ARIMA model
7. Create the Holt-Winters Exponential Smoothing model (HWE)
8. Evaluate the models
9. Forecast 36 months forward

## Dependencies

numpy
pandas
matplotlib
scipy
statsmodels
pmdarima
scikit-learn

## Dataset

The dataset used is AirPassengers.csv. It consists of monthly airline passenger numbers from 1949 to 1960.

Steps

- Define the Problem: We want to analyze and predict the amount of airline passengers in the future of at least 12 months.
- Collect and clean the data: Load the dataset and ensure it's in the correct structure.
- Explore and visualize the data: Graphically explore the characteristics of the time series (seasonality, trend, autocorrelation).
- Test for stationarity: Perform the Dickey-Fuller test to check if the time series is stationary.
- Make the time series stationary: Use decomposition and differencing techniques to make the time series stationary.
- Create the ARIMA model: Build an ARIMA model to forecast the number of airline passengers.
- Create the Holt-Winters Exponential Smoothing model (HWE): Build a Holt-Winters Exponential Smoothing model to forecast the number of airline passengers.
- Evaluate the models: Compare the performance of the ARIMA and HWE models using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
- Forecast 36 months forward: Use the best-performing model to forecast the number of airline passengers for the next 36 months.

## Results

The Holt-Winters Multiplicative model performs the best with the lowest RMSE and MAPE. The model is then used to forecast the number of airline passengers for the next 36 months.
