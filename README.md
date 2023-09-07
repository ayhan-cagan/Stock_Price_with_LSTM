# Stock Price Prediction with LSTM

## Overview
This project aims to create a machine learning model using Long Short-Term Memory (LSTM) to predict stock prices using historical data obtained from Yahoo Finance. It demonstrates the challenges and complexities of financial forecasting.

## Data
The financial data used for this project is sourced from Yahoo Finance and is stored in a CSV file named "MSFT.csv". The data includes the following columns:
- Date: The date of the stock price data.
- Close: The closing price of the stock on the given date.

## Data Preprocessing
- Missing values in the dataset are interpolated using the linear method.
- Data is divided into time windows for model training and testing.
- Data is scaled using StandardScaler.

## Model Architecture
The machine learning model is constructed using TensorFlow's Keras API. The model architecture consists of:
- An input layer with a shape of (3, 1).
- An LSTM layer with 64 units.
- Two dense layers with 32 units and ReLU activation functions.
- A final dense layer with 1 unit.

## Training
The model is trained using Mean Squared Error (MSE) as the loss function and the Adam optimizer with a learning rate of 0.001. The training process is conducted for 100 epochs.

## Evaluation
The model's performance is evaluated using Mean Absolute Error (MAE) as a metric. The evaluation results are displayed after training.

## Results
The project includes the following visualizations:
- Stock price plots for training, validation, and testing datasets.
- Training predictions compared to actual observations.
- Validation predictions compared to actual observations.
- Testing predictions compared to actual observations.
- Recursive predictions compared to actual observations.

## Usage
You can clone this repository and run the code in your own environment to experiment with stock price prediction using LSTM.

## Dependencies
- Python 3.x
- Libraries: pandas, numpy, seaborn, datetime, matplotlib, scikit-learn, TensorFlow


AYHAN CAGAN

Feel free to reach out if you have any questions or suggestions for improvements.

