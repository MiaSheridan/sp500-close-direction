
SPY Price Movement Prediction (2015–2025)

This project aims to predict whether the S&P 500 (SPY ETF) will close higher or lower the next day using historical price data.
It’s a binary classification problem, where the target variable is 1 if tomorrow’s close > today’s, and 0 otherwise.

Project Overview

Data Collection:

Historical SPY data downloaded using yfinance from 2015 to 2025.

Feature Engineering:

Created financial indicators such as daily returns, moving averages, volatility, and momentum.

Exploratory Analysis:

Visualized price trends and return distributions.

Built a correlation heatmap to examine relationships between features and target.

Model Preparation:

Split data into training (80%) and testing (20%) sets for supervised learning.

Next Steps:

Trained models such as Logistic Regression, Random Forest, and LSTM to predict the target variable.

Technologies Used

Python 3.10

Libraries:
pandas, numpy, matplotlib, seaborn, yfinance, scikit-learn
