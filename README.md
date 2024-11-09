**Problem Statement:** This project aims to analyze sales trends and patterns in the Wholesale Trade of Alcoholic Beverages using time series analysis. The goal is to identify seasonal fluctuations, anomalies, and forecast future sales, providing insights for better decision-making, strategic planning, and proactive management of peak and off-peak periods.


**Data:** The dataset consists of monthly wholesale trade sales and inventory data for Beer, Wine, and Distilled Alcoholic Beverages, spanning from January 2013 to December 2023. Each row represents a specific month, with the "Month-Year" formatted as "Jan-13" for January 2013. The data is sourced from the U.S. Census Bureau – Business and Industry Time Series Datasets, covering sales figures for the specified time period.


**Tools & Libraries:** RStudio (IDE), forecast(Package), zoo (Package)


**Methods:** 

1. Descriptive Analytics (Time series plot, Stl() PLOT, CORRELOGRAM - ACF ()

2. Data Preprocessing: The dataset was preprocessed to ensure quality: duplicates were removed, missing values addressed, and columns standardized.  The "Period" column was converted to date format using as.Date(), and the "Value" column was standardized as numeric by removing extraneous commas. 

3. Applying Forecasting Methods:
The project follows the eight-step forecasting process, applying several advanced models to analyze U.S. beverage sales data:

  *Holt-Winters Exponential Smoothing:* Captures both seasonal and trend components.

  *Regression Models:* Linear Trend, Quadratic Trend, Seasonal Model, Linear Trend with Seasonality, Quadratic Trend with Seasonality, 

  *ARIMA-Based Models:* AR(1) Model: Simple autoregressive approach.

  *ARIMA Model:* Autoregressive Integrated Moving Average for handling non-seasonal trends.

  *Seasonal ARIMA:* Extends ARIMA to account for seasonality.

  *Auto ARIMA:* Automates parameter selection for optimal ARIMA configuration. 


Evaluation:

Forecasting models are evaluated using metrics - Root Mean Squared Error (RMSE): Measures the average magnitude of forecast errors, 
Mean Absolute Percentage Error (MAPE): Evaluates the percentage accuracy of predictions.


**Outcome:**

