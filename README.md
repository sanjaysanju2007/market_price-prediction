# Stock Market Price Prediction Using LSTM

## 1. Project Overview
The Stock Market Price Prediction project uses Machine Learning and Deep Learning techniques to predict future stock prices based on historical stock market data.

In this project, an LSTM (Long Short-Term Memory) neural network is used to learn patterns from previous stock prices and predict future prices.

## 2. Problem Statement
A financial analyst wants to predict future stock prices using historical market data. The goal is to build a model that learns past price movements and generates predicted stock prices.

## 3. Objectives
- Collect historical stock price data.
- Preprocess and normalize the data.
- Train an LSTM model to learn stock price patterns.
- Predict stock prices using the trained model.
- Compare actual and predicted prices.
- Display the predicted prices in the console.

## 4. Technologies Used
- **Programming Language:** Python
- **Framework:** TensorFlow / Keras
- **Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn
- **Model:** LSTM (Long Short-Term Memory)
- **Environment:** Google Colab or Jupyter Notebook

## 5. Algorithm Used
### LSTM (Long Short-Term Memory)
LSTM is a type of Recurrent Neural Network (RNN) designed to learn patterns in sequential data.

It is suitable for time-series problems because it can learn relationships between past and future values.

## 6. Project Workflow
1. Load historical stock price data.
2. Select the stock price column.
3. Normalize the data using MinMaxScaler.
4. Create sequences of previous stock prices for training.
5. Split the data into training and testing sets.
6. Build the LSTM neural network.
7. Train the model using 100 epochs (or the configured number of epochs).
8. Predict prices using the test data.
9. Convert predicted values back to the original price scale.
10. Display actual and predicted prices in the console.

## 7. Model Training
The dataset is divided into training and testing sets. The training data helps the model learn historical price patterns, while the testing data evaluates its performance on unseen observations.

The model uses the following training parameters:
- **Model:** LSTM
- **Epochs:** 100 (configured maximum)
- **Optimizer:** Adam
- **Loss Function:** Mean Squared Error (MSE)

Note: The actual training duration and number of completed epochs may vary depending on the code, callbacks, and dataset.

## 8. Output
The program displays the actual stock prices and the corresponding predicted stock prices in the console.

Example:

```text
Actual Price     Predicted Price
150.25           151.10
152.40           152.05
154.10           153.60
155.75           155.20
```

*The values above are examples only, not actual market predictions.*

## 9. Advantages
- Learns patterns from historical price sequences.
- Supports time-series forecasting.
- Provides a comparison between actual and predicted prices.
- Helps demonstrate the application of deep learning in finance.

## 10. Limitations
- Stock prices are affected by unpredictable market events.
- Model accuracy depends on data quality and training settings.
- Historical trends do not guarantee future performance.
- Predictions are not guaranteed to be accurate.

## 11. How to Run the Project
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries if they are not already available.
3. Load the historical stock price dataset.
4. Run the code cells in order.
5. Train the LSTM model.
6. View the actual and predicted prices in the console.

## 12. Conclusion
This project demonstrates how LSTM deep learning models can be used for stock market price prediction. By learning from historical stock prices, the model generates predictions that can be compared with actual values to evaluate performance.

**Disclaimer:** This project is intended for educational purposes only. It does not provide financial advice or guarantee future stock market performance.
