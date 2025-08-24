# deep-learning-and-nlp-tesla-project
Predicting daily stock trends by combining time-series price data with a sentiment index from financial news. Includes EDA, classical ML models, LSTM, performance evaluation, and insights showing improved accuracy with sentiment integration.

This project focuses on predicting daily stock market trends by combining time-series stock price data with sentiment extracted from financial news headlines.
The workflow includes all key stages: data loading, exploratory data analysis (EDA), feature engineering, model building, performance evaluation, and model comparison.

Historical stock price data was retrieved using yfinance, alongside financial news headlines covering the same time frame. The data was cleaned, synchronized, and explored with statistical and visual analyses, including price volatility, correlations, and headline patterns.

Multiple models were developed and tested:

Classical machine learning models, such as Logistic Regression and Random Forest, trained on numerical stock market features.

An LSTM time-series model, designed to capture sequential patterns and predict next-day price movement more effectively.

To enrich the models, a daily sentiment index was generated from the news headlines, converting text into numeric sequences and aggregating them to a daily score. This sentiment score was then integrated into both the classical and deep learning models to evaluate its impact on prediction accuracy.
Results are presented using performance tables, confusion matrices, and visual comparisons between actual and predicted value
