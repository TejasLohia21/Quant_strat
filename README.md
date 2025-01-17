Cryptocurrency Trading Strategies and Market Regime Model

Overview

This repository contains implementations of various cryptocurrency trading strategies focused on Ethereum and Bitcoin. The strategies leverage technical indicators, machine learning models, and risk management techniques to optimize trading decisions. A key component is the Market Regime Model, which classifies the market into different regimes based on financial indicators, helping to predict market conditions and make informed trading decisions. 

The final model is under development.

Trading Strategies

Key Features
	•	Fibonacci Retracements: Dynamically adjusted retracements used in conjunction with a Market Regime Prediction model.
	•	Neural Network: Trained on signals from Fibonacci models to enhance predictions.
	•	Market Regime Model: Based on GARCH models and technical indicators to classify market conditions.
	•	Risk Management: Incorporates covariance analysis and Value at Risk (VaR) models for effective risk control.

Market Regime Model

Objective

The Market Regime Model aims to classify the market conditions as Bullish, Bearish, or Sideways based on technical and statistical indicators. This helps in predicting market behavior and making strategic trading decisions.

Feature Engineering

The model computes several key financial metrics:
	•	Returns & Log Returns: Capture daily price changes.
	•	Volatility: Measure of price fluctuations over time.
	•	RSI (Relative Strength Index): Indicates overbought or oversold market conditions.
	•	MACD (Moving Average Convergence Divergence) Difference: Identifies trend strength and direction.
	•	Bollinger Bands: Determine overbought or oversold levels based on price volatility.
	•	GARCH Volatility: Uses a GARCH model to estimate volatility, which is essential for risk assessment and market condition classification.

Clustering and Classification
	•	KMeans Clustering: The model applies KMeans clustering to categorize the market into distinct regimes.
	•	Silhouette Score: Used to determine the optimal number of clusters for accurate market classification.
	•	Volatility Thresholds: Classifies market volatility into High, Moderate, or Low based on standard deviation calculations.

Current Development

The model is under active development to incorporate advanced concepts like LSTM (Long Short-Term Memory) networks and more mathematically robust quantitative models to improve predictions and decision-making.

Usage
	1.	Feature Engineering: Processes raw market data to extract meaningful features.
	2.	Model Initialization: Sets up clustering models using historical data.
	3.	Market Condition Prediction: Predicts the current market regime and volatility level based on recent data.

Risk Management
	•	Covariance Analysis: Evaluates the relationship between different assets to minimize portfolio risk.
	•	VaR (Value at Risk): Estimates potential losses in a portfolio, helping to set risk limits and manage exposure.

Future Enhancements
	•	Incorporation of LSTM Networks: To capture temporal dependencies and improve the accuracy of market predictions.
	•	Quantitative Models: Backed by robust mathematical theories to enhance decision-making processes.

Contribution

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request. Please ensure all new features or bug fixes are accompanied by tests.

License

This project is licensed under the MIT License. See the LICENSE file for details.

This README provides a comprehensive overview of the project, detailing the trading strategies, market regime model, and future development plans.
