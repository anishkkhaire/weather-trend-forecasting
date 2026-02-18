## Weather Trend Forecasting

This project analyzes global weather data and builds a simple model to forecast temperature trends over time.

## Dataset  
Global Weather Repository  
https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository

The dataset contains daily weather information for locations around the world, including temperature, precipitation, wind, and air quality data.

## Tools Used  
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Statsmodels

## What I Did  
I started by loading the dataset and converting the `last_updated` column into a proper datetime format.  
Rows with missing temperature or timestamp values were removed.  
To keep the analysis simple and clear, I selected one city with the most available data.

## Exploratory Analysis  
I plotted temperature trends over time to understand patterns and seasonality.  
Basic visualizations helped identify how temperature changes across days.

## Forecasting  
A SARIMA time-series model was used to forecast temperature for the next 30 days using historical data.  
The model was trained on past observations and evaluated on recent data.

## Evaluation  
Model performance was measured using:
MAE ≈ 4.13 °C  
RMSE ≈ 5.42 °C  

## Conclusion  
The model was able to capture general temperature trends and provide reasonable short-term forecasts.  
This project demonstrates basic data cleaning, exploratory analysis, time-series forecasting, and evaluation.

## PM Accelerator  
This project aligns with the PM Accelerator mission of encouraging practical, hands-on experience in data analytics and machine learning.
