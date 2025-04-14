# Weather Trend Forecasting

## Overview
This project focuses on analyzing global weather data and forecasting future weather trends using various machine learning and time series models. The dataset includes weather metrics from multiple locations worldwide, such as temperature, humidity, wind speed, and air quality indices. The goal is to predict future weather patterns and identify trends using advanced forecasting techniques.

## Features
- **Data Cleaning and Preprocessing**: Handles missing values, removes duplicates, and normalizes numerical features.
- **Exploratory Data Analysis (EDA)**: Analyzes trends, correlations, and outliers in the dataset.
- **Forecasting Models**: Implements multiple models for weather trend prediction, including:
  - **Exponential Smoothing (ETS)**
  - **Prophet**
  - **ARIMA**
- **Ensemble Forecasting**: Combines predictions from multiple models for improved accuracy.
- **Visualization**: Generates plots to compare actual vs. forecasted weather trends.

## Dataset
The dataset, `GlobalWeatherRepository.csv`, contains 58,853 entries with 41 columns, including:
- Location details (country, latitude, longitude, timezone)
- Weather metrics (temperature, humidity, wind speed, precipitation, etc.)
- Air quality indices (CO, Ozone, PM2.5, etc.)
- Time-based features (last updated, sunrise, sunset
