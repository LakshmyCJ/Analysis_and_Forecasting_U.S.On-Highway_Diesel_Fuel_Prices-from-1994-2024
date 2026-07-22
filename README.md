# 🚛 U.S. On-Highway Diesel Fuel Price Forecasting (1994–2024)

## Overview
This project analyzes and forecasts monthly U.S. on-highway diesel fuel prices using 30 years of historical data from the U.S. Energy Information Administration (EIA). Multiple time series forecasting models were developed and compared to identify the most accurate approach for predicting future fuel prices and supporting data-driven business decisions.

## Objectives
- Analyze long-term trends and seasonality in diesel fuel prices
- Build and compare multiple forecasting models
- Evaluate model performance using cross-validation
- Generate a reliable 36-month price forecast

## Dataset
- **Source:** U.S. Energy Information Administration (EIA)
- **Time Period:** April 1994 – October 2024
- **Frequency:** Monthly
- **Target Variable:** U.S. On-Highway Diesel Fuel Price ($/gallon)

## Tools & Technologies
- R
- tidyverse
- fpp3
- tsibble
- fable
- ggplot2

## Models Developed
- Time Series Regression (TSLM)
- Manual ETS
- Auto ETS
- ARIMA
- Auto ARIMA
- Ensemble Forecasting

## Key Results
- Identified long-term trends, seasonality, and major price shocks.
- Compared models using RMSE, MAE, MAPE, and cross-validation.
- Built an ensemble model combining TSLM, ETS, and ARIMA using inverse variance weighting.
- Generated a 36-month operational forecast with prediction intervals.

## Business Impact
This forecasting framework can support:
- Transportation and logistics planning
- Fuel cost budgeting
- Supply chain decision-making
- Energy market analysis
- Business and policy planning
