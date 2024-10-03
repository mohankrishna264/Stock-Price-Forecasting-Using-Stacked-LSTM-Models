# Stock Market Price Prediction by LSTM
## Overview
This project focuses on predicting stock prices using Long Short-Term Memory (LSTM), a type of Recurrent Neural Network (RNN). The model is built to forecast the stock prices of two major companies: Google and Apple.

## Key Features:
Predicts the stock price using LSTM, which is particularly useful for time series data.
Works with historical stock data from 2016 to 2021, using each day's closing price.
The model predicts the next day's stock price based on the last 100 days of closing prices.
## Data Source:
The stock data is fetched from the Tiingo API. To access the data, you will need to:
Sign up on the Tiingo website (https://www.tiingo.com).
Obtain your API key after logging in (please keep this key private).
## Dataset:
The original dataset is available on Kaggle (https://www.kaggle.com/karan842/stock-price-prediction-lstm). You can use this dataset for training and testing the model.

## Data Collection: The historical stock prices are fetched using the Tiingo API. This project works specifically with the daily close price of stocks.
## Data Preprocessing: The last 100 days of data are used to predict the next day's stock price.
LSTM Model: The LSTM model is trained on the historical data to make predictions.
Prediction: The model predicts the stock price for the next day based on the recent trends in the closing prices.
## How to Run:
Clone or download the project files.
Sign up for the Tiingo API (https://www.tiingo.com) and get your API key.
Fetch the stock data by following the instructions in the notebook.
Run the Jupyter notebook to train the LSTM model and make predictions.
## Kaggle Notebook:
The code for this project is also posted on Kaggle (https://www.kaggle.com/karan842/stock-price-prediction-lstm), where the dataset and detailed code are available for reference.

## Conclusion:
This project demonstrates how LSTM models can be used for time series forecasting, particularly for stock prices. By leveraging historical data, we can make informed predictions about future stock prices.

FOLLOW ME ON LINKEDIN https://www.linkedin.com/in/mohan-krishna-kola/
