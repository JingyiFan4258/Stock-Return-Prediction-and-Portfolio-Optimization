# Stock-Return-Prediction-and-Portfolio-Optimization

We select stock prices of Apple Inc. (AAPL), IBM, and Amazon.com, Inc. (AMZN) and apply machine learning models (i.e. 1D CNN, Simple RNN, LSTM, and GRU) to find the best fitted time series forecasting models for a single time step. We apply the Monte Carlo simulation method and calculate the Sharpe ratio to find the most optimal assignment of portfolio weights. Finally, we apply the estimated weights and predicted stock return to calculate the portfolio return for the next day.

# Introduction
There’s a widespread assumption in investing that higher risk equals increased potential returns. Thus, the main goal for investors is to find the optimal weights for each asset and predict the most substantial possible return given a specific portfolio. In this project, our aim is to use different financial stock prices from Yahoo Finance to find best fitted time series forecasting Models for a single time step. The specific models we employ are CNN, Simple RNN, LSTM and GRU that we've been exposed to during this class. 

Our project could be divided into three parts:
1. Using time series data and the WindowGenerator class, we could predict 1 step further and find the best fitted model by measuring and comparing the model’s performance.
2. Analyze the best investment portfolio via Monte Carlo Simulation and choose the optimal asset allocation with the selected stocks.
3. We combine the results from part 1 and 2 and derive the optimal return in the 1 step further.
