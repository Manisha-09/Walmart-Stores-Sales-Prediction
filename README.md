# Walmart Stores Sales Prediction

## Project Overview
This project aims to predict weekly sales for Walmart stores across different departments. Accurate sales predictions are crucial for inventory management, staffing, and overall operational efficiency. By leveraging various machine learning models, this project explores different approaches to enhance the accuracy of sales forecasts.

## Dataset
The dataset includes historical sales data, store information, and macroeconomic factors that could impact sales, such as holidays and weather conditions.

## Key Features
- **Store and Department Information**: Identifies the store and department for each sales record.
- **Weekly Sales Data**: Historical sales data across multiple weeks.
- **Holiday Flags**: Indicator of whether a particular week contains a holiday.
- **Temperature, Fuel Price, and CPI**: External economic factors that might influence sales.

## Models and Techniques
- **Linear Regression**: A simple baseline model to understand the basic relationship between the features and sales.
- **Random Forest Regressor**: A powerful ensemble learning method that captures complex interactions between features.
- **XGBoost**: An advanced gradient boosting algorithm used to improve prediction accuracy and handle overfitting.
- **Time Series Analysis**: Incorporating time series components to capture seasonality and trend effects in the sales data.

## Evaluation Metrics
- **Mean Absolute Error (MAE)**: Used to measure the average magnitude of errors in predictions.
- **Root Mean Square Error (RMSE)**: Provides a quadratic scoring method that penalizes larger errors.

## Results
The XGBoost model achieved the best performance, outperforming baseline models by capturing complex patterns in the data. Time series analysis further enhanced the predictions by considering seasonal trends.

