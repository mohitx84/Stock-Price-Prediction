# 📈 Stock Price Prediction Using LSTM

This project demonstrates how to forecast stock prices using Long Short-Term Memory (LSTM) neural networks. It uses historical Apple Inc. (AAPL) data from Yahoo Finance to train a deep learning model that predicts future closing prices.

## 🔧 Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- yFinance API
- Matplotlib

## 📊 Workflow
1. **Data Collection**: Fetched historical AAPL stock data using yFinance.
2. **Data Preprocessing**: Normalized price data using MinMaxScaler, created sequences for LSTM.
3. **Model Architecture**: Two-layer LSTM network with Dense output.
4. **Training**: Model trained on 60-day windows of historical prices.
5. **Evaluation**: RMSE used to evaluate model accuracy on test data.
6. **Visualization**: Actual vs. predicted prices plotted to analyze performance.

## 📈 Output
The model effectively learns temporal trends and generates future stock closing price predictions, visualized using Matplotlib.
