## Citi Bank Stock Price Prediction Using Machine Learning ##

- This project investigates the effectiveness of various machine learning models in predicting the stock price of Citi Bank (Ticker: C) using historical stock data and macroeconomic indicators.

**Overview**

- Four regression models were implemented and compared:
1. Decision Tree Regressor
2. Random Forest Regressor
3. K-Nearest Neighbors (KNN)
4. Support Vector Regressor (SVR)

**Key Findings**

- Random Forest Regressor delivered the best performance with an R² score of 0.95 and Mean Directional Accuracy (MDA) of 0.5295.
- Strong positive correlations were observed with features like SPY, JPM, and WFC, validating their inclusion.
- SVR and KNN showed poor predictive performance, while the Decision Tree model struggled with dynamic market shifts.

**Features Used**

- Stock prices of peer financial institutions: JPMorgan Chase (JPM), Morgan Stanley (MS), Wells Fargo (WFC)
- Macroeconomic indicators: Crude Oil (CL=F), Gold (GC=F), Dollar Index (DX-Y.NYB), 10-Year Treasury Yield (^TNX), S&P 500 ETF (SPY), Volatility Index (^VIX)

**Tools & Techniques**

- Python (pandas, scikit-learn, matplotlib, seaborn)
- Data preprocessing, correlation analysis, feature scaling
- Cross-validation for hyperparameter tuning
- Evaluation metrics: R², MSE, RMSE, and MDA

**Next Steps**

- Incorporate sentiment analysis and financial news as features
- Explore deep learning approaches like LSTM for time series forecasting
- Integrate ARIMA or hybrid models for improved accuracy

**Conclusion**

- This project highlights the power of ensemble learning and the importance of selecting meaningful, macro-aware features in financial forecasting. The findings demonstrate how machine learning can enhance prediction accuracy in complex and volatile financial markets.

