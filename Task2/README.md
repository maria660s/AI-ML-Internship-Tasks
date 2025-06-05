# Task 2: Predict Future Stock Prices (Short-Term)

## Task Objective
The goal of this task is to predict the next day’s closing price of a selected stock using historical stock market data. This involves leveraging features such as Open, High, Low, and Volume to train a machine learning model that can forecast short-term stock price movements.

## Dataset Used
Historical stock data was retrieved using the `yfinance` Python library. The dataset includes daily stock prices with features such as Open, High, Low, Close, and Volume for the selected stock (e.g., Apple Inc.).

## Models Applied
- **Random Forest Regressor:** An ensemble learning method that builds multiple decision trees and aggregates their results for improved prediction accuracy.

## Key Results and Findings
- Random Forest models was trained and evaluated on the historical stock data.
- The Random Forest model demonstrated better predictive performance with lower mean squared error.
- Plots comparing actual vs predicted closing prices highlight the Random Forest’s ability to more closely follow the real stock price trends.
- This approach provides a foundation for short-term stock price prediction, though more complex models and additional features may improve results further.
