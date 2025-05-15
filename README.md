# META_STOCK_Time_Series_Forecasting
This is a project of forecasting META stock prices historical data for close prices from Yfinance using ARIMA, ARCH and GARCH modelling.
It is submitted as part of course assignment for Time Series Analysis for Bachelor's degree in Data Science.
## 📊 Contents

- Download of historical stock prices using `yfinance`
- Stationarity checks using the Augmented Dickey-Fuller (ADF) test
- Autocorrelation analysis using ACF and PACF plots
- ARIMA modeling for forecasting
- ARCH modelling for volatility analysis
- GARCH modeling for volatility analysis
- Interpretation of results and model comparison
- ARCH and GARCH volatility comparison

## 📈 Models Used

- **ARIMA(1,1,1)**: Based on differencing and ACF/PACF diagnostics
- **ARCH(1)**:Based on autoregression
- **GARCH(1,1)**: Applied to model volatility clustering in returns

## 📦 Libraries Used

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `yfinance` for data fetching
- `statsmodels` for ARIMA modeling
- `arch` for GARCH modeling
