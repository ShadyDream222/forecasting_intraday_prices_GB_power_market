# Forecasting Intraday Prices in GB Power Market

**Contributeur** : GUIDDIR Lucas 

## Project Overview
This project aims to forecast Intra-Day electricity prices in the Great Britain power market, using publicly available data known in advance (e.g., Day-Ahead prices, generation, demand forecasts, system margins).


## Installation & Setup
### 1. Clone the repository
```
git clone <repository-url>
cd GB_power_market_intraday_ForecastProject
```

### 2. Run the Jupyter Notebook
```
jupyter notebook GB_power_market_intraday_ForecastProject.ipynb
```

## Analysis Summary
The project includes:

- Importing and preprocessing electricity market data from the GB power system (BMRS)
- Performing time series analysis on Intra-Day and Day-Ahead prices to detect trends, seasonality, and volatility
- Engineering features from generation forecasts, demand forecasts, and calendar variables
- Building and evaluating a SARIMAX model with exogenous variables to capture temporal dynamics
- Training an XGBoost model with GridSearchCV to capture nonlinear patterns and improve forecast accuracy
- Visualizing trends, residuals, predictions, and feature impacts using Matplotlib, Seaborn, and SHAP



## Future Enhancements

- Applying GARCH models to better capture price volatility
- Completing SHAP-based model explainability for the XGBoost model
- Comparing against other ML models for benchmarking

