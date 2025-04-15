# Stock-Price
# Objective
The goal of this project is to develop, implement, and evaluate deep learning models for forecasting the stock price of Apple Inc. (AAPL). By leveraging historical stock price data sourced from Yahoo Finance, we aim to build robust models that can predict future stock trends using temporal patterns in the data.

The models explored in this project include:
*Long Short-Term Memory (LSTM)
*LSTM for Future Price Prediction
*Gated Recurrent Unit (GRU)
*Transformer-Based Model

# Dataset
Source: Yahoo Finance
Stock Ticker: AAPL (Apple Inc.)
Data Features: Date, Open, High, Low, Close, Adj Close, Volume
Time Range: Customizable using yfinance API (e.g., 2010–2024)

# Models Implemented
LSTM (Long Short-Term Memory)
Captures long-term dependencies in stock data.
Used for next-day price prediction.

Future Prediction with LSTM
Predicts prices multiple days into the future.
Uses recursive or sequence-based prediction.

GRU (Gated Recurrent Unit)
A more efficient RNN variant.
Less complex and faster training than LSTM.

Transformer
Attention-based model suitable for time series.
Captures global temporal patterns effectively.

# Evaluation Metrics
To assess model performance:
Mean Squared Error (MSE): Measures average squared difference between predicted and actual values.
Mean Absolute Error (MAE): Measures average magnitude of errors.
R-Squared (R²): Indicates proportion of variance explained by the model.

# Technologies Used
Python
NumPy, Pandas, Matplotlib, Seaborn
Scikit-learn
TensorFlow / Keras
PyTorch (optional)
yfinance

