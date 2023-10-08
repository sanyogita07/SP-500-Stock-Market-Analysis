# Predicting S&P 500 Movements: A Data Analysis Approach
# Overview
This repository delves into a detailed analysis of the S&P 500 index using Yahoo Finance data. The project not only visualizes historical trends but also preps data for predictive modelling. Key features include training a RandomForestClassifier, backtesting its predictions, and analyzing correlations with the Nikkei 225 index. The project concludes with a feature importance evaluation to understand the key drivers behind the model's predictions.

# Problem Statement:
How effectively can we predict the S&P 500 index movements using its historical data and its correlation with the Nikkei 225 index?

# Approach:
Data Collection: Sourced the S&P 500's comprehensive historical data from Yahoo Finance.

Data Cleaning: Refined the dataset by excluding non-essential columns, resulting in 7,074 overlapping data points post-timezone adjustments.

Modelling: Implemented a RandomForestClassifier using features such as closing prices, volume, and more.

Backtesting: Subjected the model's predictions to real-world outcomes to ensure its reliability.

Enhancement: Incorporated Nikkei 225 data, revealing a correlation coefficient of approximately 0.179 with the S&P 500's daily changes.

# Findings:
The RandomForest model achieved a precision of 0.46 with enhanced predictors.
A mild positive correlation exists between the daily changes of the S&P 500 and the Nikkei 225.
Feature importance analysis highlighted the most influential predictors in the model.

# Tools Utilized:
yfinance, sklearn, matplotlib, seaborn.
