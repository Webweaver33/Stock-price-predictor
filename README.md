# Stock Price Predictor using LSTM

This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices for Indian stocks using historical data. 
The model is built using Python and leverages libraries such as TensorFlow, Keras, and Yahoo Finance for data retrieval. The implementation is provided in a Jupyter Notebook.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [License](#license)

## Features

- Fetch historical stock price data from Yahoo Finance.
- Preprocess the data for LSTM model training.
- Train an LSTM model to predict future stock prices.
- Visualize training history and predicted prices.
- Print the predicted stock price for the next day.

## Requirements

Make sure you have Python 3.x installed. This project requires the following Python libraries:

- numpy
- pandas
- yfinance
- matplotlib
- tensorflow
- scikit-learn

## Installation

1. Clone this repository:
   ```bash

   git clone https://github.com/yourusername/stock-price-predictor.git
   cd stock-price-predictor
2. Install the required libraries:
bash
pip install -r requirements.txt
Alternatively, you can install the libraries individually:
bash
pip install numpy pandas yfinance matplotlib tensorflow scikit-learn

Usage
Open the Jupyter Notebook stockprice_predictor.ipynb in your favorite Jupyter environment (e.g., Jupyter Notebook, JupyterLab).
Modify the stock_symbol variable in the notebook if you want to predict a different stock (e.g., change it to 'TCS' for Tata Consultancy Services).
Run the cells in the notebook sequentially to execute the code and obtain predictions.
The predicted price for the specified stock will be printed in Indian Rupees (INR).

Example
When you run the notebook, you should see output similar to:
text
The predicted price for RELIANCE is: ₹2450.50

This indicates that the model predicts that the next day's price for Reliance Industries Limited will be ₹2450.50.
