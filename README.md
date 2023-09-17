# openingrangestudyCL

Stock Market Analysis Using Python
This repository contains Python code for analyzing stock market data with a specific focus on the opening 30 seconds and the first 30 minutes of the trading day. The analysis aims to identify patterns that can be useful for trading strategies.

Features
Data Preprocessing: Cleans and filters 252 days of stock data, aligning it to focus on the opening market ranges.

Statistical Measures: Calculates key trading indicators like opening range, first 30-minute range, and opening volume to form a comprehensive dataset.

Clustering Analysis: Utilizes KMeans clustering to categorize different trading days into clusters based on opening range, first 30-minute range, and opening volume.

Data Visualization: Provides scatter plots and histograms for visual interpretation of the clusters and their key characteristics, helping to identify trends and correlations.

Use Case
The code computes a "30-second opening range multiple" which serves as a useful predictor for the day's trading volatility and price movement. This analysis can be integrated into trading algorithms for more data-driven decision-making.

Requirements
Python 3.x
pandas
matplotlib
seaborn
scikit-learn
How to Run
Clone the repository.
Add your stock data CSV in the appropriate directory.
Run the Python script.
Feel free to adjust as needed!
