# Stock Price Prediction Project

## Overview
This project develops a machine learning model to predict stock closing prices 5 trading days into the future. The solution combines technical analysis, feature engineering, and multiple modeling approaches to achieve both statistical accuracy and practical trading value.

## Key Features
- Comprehensive exploratory data analysis of stock price patterns
- Feature engineering incorporating technical indicators and temporal features
- Multiple prediction models including Linear Regression, Random Forest, XGBoost, and LSTM
- Evaluation using both statistical metrics and directional accuracy

## Repository Structure
- `stock_prediction.ipynb`: Main Jupyter notebook with complete analysis and code
- `eda_report.pdf`: Detailed exploratory data analysis report
- `model_selection.pdf`: Documentation of model comparison and selection process
- `predictions.csv`: CSV file with predictions for the test period
- `README.md`: This file

## Requirements
- Python 3.8+
- Required packages: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, xgboost, tensorflow, keras

## How to Reproduce Results
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook stock_prediction.ipynb`
4. The notebook is structured sequentially and can be run from top to bottom

## Key Findings
- Technical indicators like RSI, MACD, and Bollinger Bands provide valuable predictive signals
- XGBoost model achieved the best balance of accuracy and interpretability
- Directional accuracy (predicting price movement direction) reached 62% on the test set
- Volume-price relationships showed significant predictive power during market volatility

## Future Improvements
- Incorporate alternative data sources (news sentiment, macroeconomic indicators)
- Implement ensemble methods combining multiple model predictions
- Develop adaptive models that can adjust to changing market conditions
