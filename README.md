# LSTM-Stock-Market-Data
This repository contains the Jupyter Notebook lstm_stock_market.ipynb, which provides an implementation of a Long Short-Term Memory (LSTM) neural network for stock market prediction using historical stock price data. This code is designed for users who want to learn how to apply deep learning techniques to time series data.

# Table of Contents
1. Installation
2. Usage
3. Model Architecture
4. Dataset
5. Data Preprocessing
6. Training and Evaluation

# Installation
1. Clone the repository
2. Launch Jupyter Notebook

# Usage
1. Open the Cnn_FCN.ipynb file in Jupyter Notebook.
2. Follow the instructions and comments provided in the notebook to understand each step of the process.
3. Execute each code cell in sequence by pressing Shift + Enter.
4. Modify the code as needed to adapt it to your own dataset or use case.

#Model Architecture
The implemented model consists of the following architecture:

1. One or more LSTM layers, each followed by dropout for regularization.
2. A dense output layer with a linear activation function for predicting the stock prices.

Dataset

https://www.kaggle.com/competitions/jane-street-market-prediction/data

This notebook assumes that you have historical stock price data available in a CSV file. The dataset should contain columns for the date, opening price, high price, low price, closing price, adjusted closing price, and trading volume. The notebook provides code for loading and visualizing the data using pandas and Matplotlib.

# Data Preprocessing
The notebook includes code for preprocessing the dataset, such as:

1. Filtering the relevant columns (e.g., adjusted closing price)
2. Scaling the data using a MinMaxScaler
3. Creating training and testing datasets with a specified lookback window

# Training and Evaluation
The notebook provides code for training the LSTM model using the Adam optimizer and mean squared error (MSE) loss function. During training, the model's performance is evaluated using the testing set, and the training progress is visualized using loss plots. After training, the notebook also provides code for visualizing the model's predictions on the test data, as well as calculating evaluation metrics such as root mean squared error (RMSE).
