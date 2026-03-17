# Energy-Consumption-Time-Series-Forecasting-
Forecast short-term household energy usage using historical time-based patterns.   
# Task Objective

The objective of this project is to perform short-term forecasting of household energy consumption using historical time-series data. The goal is to analyze temporal patterns in electricity usage and build predictive models that can accurately estimate future energy demand.

This task focuses on applying time series forecasting techniques and comparing multiple models to identify the most effective approach.
# Your Approach

In this project, the following steps were performed:

- Data Loading & Preprocessing:
The Household Power Consumption dataset was loaded, and date-time columns were combined to create a proper time index. Missing values were handled and the data was resampled into hourly intervals.

- Feature Engineering:
Time-based features such as hour, day, month, weekday, and weekend indicators were created to capture temporal patterns in energy consumption.

- Exploratory Data Analysis (EDA):
Trends and patterns in energy usage were analyzed using visualizations, including overall consumption trends and hourly usage behavior.

- Model Building:
  
Three different models were implemented:

   - ARIMA for statistical time series forecasting

   - Prophet for handling seasonality and trends

   - XGBoost for machine learning-based prediction using engineered features

- Model Evaluation:
Models were evaluated using:

   - Mean Absolute Error (MAE)

   - Root Mean Squared Error (RMSE)

- Visualization:
Actual vs predicted values were plotted to visually compare model performance.

# Results and Findings

- Energy consumption shows clear daily and weekly patterns, with higher usage during specific hours of the day.

- Feature engineering significantly improved model performance, especially for machine learning models.

- XGBoost performed the best, as it effectively captured complex patterns using time-based features.

- ARIMA performed reasonably well for trend-based forecasting but struggled with non-linear patterns.

- Prophet handled seasonality effectively and provided stable predictions.
# Key Insights:

- Energy usage peaks during morning and evening hours

- Weekend consumption patterns differ from weekdays

- Machine learning models outperform traditional methods when meaningful features are available
