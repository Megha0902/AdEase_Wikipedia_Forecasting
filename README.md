# Ad_Ease Wikipedia Page Views Forecasting
Time series forecasting project for Wikipedia page views to optimize ad placements using Python.(Using ARIMA/SARIMA/Prophet) Model


## Project Overview
Ad_Ease aims to forecast Wikipedia page views (145k pages, 550 days, multiple languages) to optimize ad placements and maximize clicks at minimum cost. Using time series forecasting and campaign data, Ad_Ease can predict traffic patterns and guide client strategies.

## Problem Statement
- Predict daily page views for Wikipedia articles.
- Incorporate external campaigns/events that affect traffic.
- Help optimize advertising strategies based on forecasted traffic.

## Dataset
- **train_1.csv**: Number of visits per article per day.
- **exog_campaign_eng.csv**: Campaign/event data for pages in English.

## Approach
1. Data Preprocessing:
   - Handling missing values
   - Converting date formats
   - Aggregating data if needed
2. Exploratory Data Analysis:
   - Visualizing traffic trends
   - Checking seasonality, trends, and outliers
3. Feature Engineering:
   - Lag features
   - Rolling averages
4. Modeling:
   - ARIMA/SARIMA/SARIMAX
   - Prophet
5. Evaluation:
   - Metrics: RMSE, MAPE
   - Visualization of predictions vs actuals

## Results
- Most pages show strong weekly seasonality.
- Campaigns/events significantly affect traffic.
- Forecasting model achieved MPE of 5% .

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Megha0902/AdEase_Wikipedia_Forecasting.git
    ```
2. Run notebooks/scripts:

    jupyter notebook notebooks/ad_ease_analysis.ipynb


