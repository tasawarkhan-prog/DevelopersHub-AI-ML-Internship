# Task 2: Stock Price Prediction

## Objective
The goal of this task is to predict the next day's closing price of a stock using historical data, including Open, High, Low, and Volume.

## Dataset
- **Dataset Name:** Historical stock data
- **Source:** Yahoo Finance (fetched using yfinance Python library)
- **Features:**
  - Open
  - High
  - Low
  - Close (target)
  - Volume

## Steps Performed
1. **Data Loading:** Retrieved stock data using `yfinance`.  
2. **Data Inspection:**  Displayed first few rows using `.head()`.
3. **Feature Selection:** Used Open, High, Low, and Volume to predict next day's Close price.  
4. **Model Training:** Applied Linear Regression for prediction.  
5. **Visualization:**
   - Line plot comparing actual vs predicted closing prices.
6. **Libraries Used:** pandas, numpy, matplotlib, yfinance, scikit-learn

## Key Findings
- Model captures short-term trends in closing prices.  
- Predictions closely follow the actual stock prices, though minor deviations occur due to market volatility.  
- Linear Regression is simple but gives reasonable short-term prediction accuracy.  
- Feature importance can be explored with more advanced models.

## Conclusion
Time series prediction of stock prices demonstrates how historical data can be used for short-term forecasting. Using regression models and visualization helps evaluate prediction performance and patterns in the stock market.
