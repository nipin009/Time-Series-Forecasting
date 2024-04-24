# Time Series Forecasting of Google's Stock Price

## Overview
Welcome to the Time Series Forecasting project focused on predicting Google's stock price! In this repository, we explore two popular techniques for time series forecasting: ARIMA (AutoRegressive Integrated Moving Average) with hyperparameter tuning and LSTM (Long Short-Term Memory) neural networks. Our goal is to build robust models capable of accurately predicting the future trends of Google's stock price based on historical data.

## ARIMA with Hyperparameter Tuning
ARIMA is a widely used statistical method for time series forecasting, capable of capturing linear relationships and seasonality in the data. In this project, we employ ARIMA models and implement hyperparameter tuning techniques to optimize model performance. We experiment with different combinations of parameters such as autoregressive order (p), differencing order (d), and moving average order (q) to find the best configuration for predicting Google's stock price.

## LSTM (Long Short-Term Memory) Networks
LSTM networks are a type of recurrent neural network (RNN) designed to capture long-term dependencies in sequential data, making them well-suited for time series forecasting tasks. In this project, we leverage the power of LSTM networks to learn complex patterns and relationships from historical stock price data. By training LSTM models on past stock prices and their corresponding sequences, we aim to forecast future price movements with high accuracy.

## Dataset
The dataset used in this project consists of historical daily stock prices of Google extracted from reliable sources such as Yahoo Finance or Google Finance. The data includes features such as opening price, closing price, highest price, lowest price, and trading volume. We preprocess the data by normalizing values and splitting it into training and testing sets for model training and evaluation.
