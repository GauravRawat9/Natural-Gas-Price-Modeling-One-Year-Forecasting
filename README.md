# Natural-Gas-Price-Modeling-One-Year-Forecasting

📌 Project Overview

This project analyzes historical monthly natural gas prices and builds a predictive model to:
Estimate the purchase price of natural gas on any historical date
Identify seasonal and structural price patterns
Extrapolate prices one year into the future
Support long-term storage contract pricing decisions
The dataset consists of monthly end-of-month natural gas prices from October 2020 to September 2024, combined with forward snapshot pricing for the next 18 months.

This project demonstrates practical applications of:
Time Series Analysis
Seasonality Detection
Forecasting & Extrapolation
Quantitative Modeling in Python

🗂 Dataset Description

Frequency: Monthly (End-of-Month)
Start Date: 31 October 2020
End Date: 30 September 2024
Data Type: Market snapshot purchase price of natural gas
Source: Market data provider (simulated financial dataset)
Each data point represents the market purchase price of natural gas delivered at the end of each calendar month.

🎯 Objectives

Load and preprocess monthly natural gas price data.
Visualize historical price movements.
Detect seasonality patterns (e.g., winter demand spikes).
Build a time series model for interpolation and forecasting.
Extrapolate prices for an additional 12 months.
Create a function that:
1) Takes any date as input
2) Returns an estimated natural gas price

📊 Exploratory Data Analysis

The analysis includes:
Time series visualization
Seasonal trend inspection (monthly patterns)
Price volatility assessment
Trend identification
Forward curve understanding
Observed potential drivers of price variation:
Winter heating demand
Supply constraints
Storage levels
Geopolitical risks
Energy market cycles

🛠 Technologies Used

Python
Pandas
NumPy
Matplotlib
Statsmodels (SARIMA / ARIMA)
Scikit-learn (optional regression comparison)

