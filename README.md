Algorithmic Trading with Machine Learning Quant Strategies

This repository includes three trading strategies leveraging machine learning and statistical modeling for algorithmic trading. The projects focus on creating strategies that are data-driven and optimized for financial performance, with an emphasis on backtesting and visualizing results.
Projects Overview
Project 1: Unsupervised Learning Trading Strategy

This strategy utilizes unsupervised machine learning to cluster stocks based on various technical indicators and risk factors. Key steps include:

    Loading SP500 stock data and calculating technical indicators (e.g., RSI, Bollinger Bands, MACD).
    Aggregating data at the monthly level and selecting the 150 most liquid stocks.
    Applying K-Means clustering to group stocks and creating a portfolio based on Efficient Frontier optimization.
    Comparing portfolio performance with SP500.

Project 2: Twitter Sentiment Trading Strategy

This project aims to leverage sentiment analysis on Twitter data to inform trading decisions:

    Fetching relevant Twitter data related to target stocks.
    Using natural language processing (NLP) to analyze sentiment trends.
    Implementing a rule-based system to make trades based on aggregate sentiment, aiming for a data-informed trading approach.

Project 3: Intraday GARCH Trading Strategy

This strategy uses the GARCH (Generalized Autoregressive Conditional Heteroskedasticity) model for intraday volatility modeling:

    Analyzing intraday SP500 data to predict volatility.
    Using GARCH predictions to inform trading decisions, leveraging volatility insights for high-frequency trading.
    Backtesting the strategy and evaluating performance metrics.

Requirements

The following Python packages are used across the projects:

    pandas, numpy, matplotlib, yfinance, sklearn, PyPortfolioOpt, and others listed in the notebook.
