# Stock-prediction-Regression-and-classification


This project explores stock price forecasting using both regression and classification approaches with the use of TensorFlow and Keras. The workflow covers data acquisition, feature engineering, and technical indicator generation,
followed by deep learning model development.

🔹 Methods
Regression Models: RNN, LSTM, BiLSTM, GRU
Task: Forecast future closing prices

Classification Models: Predict stock price movement direction (up/down)
🔹 Key Findings
Regression Results:
Base RNN: MSE = 18.31, MAE = 2.86
Best GRU: MSE = 15.09, MAE = 2.47 (improved accuracy)

Classification Results:
Base RNN: 76.18% accuracy
F1-score (class 1): 0.803
Best BiLSTM: 86.11% accuracy
F1-score (class 1): 0.885

🔹 Conclusion

By combining regression (price prediction) and classification (direction prediction), along with visualizations and error analysis, the models achieve improved accuracy and
robustness in financial time series forecasting.
