# 💰 💱 💴 Forecasting_Yen_Vs_USD 💴 💱 💰
Time-Series Forecasting and Linear Regression Forecasting of the Japanese Yen to the US Dollar

* [Time_Series_Analysis](https://github.com/BenMcCright/Forecasting_Yen_Vs_USD/blob/master/Notebooks/regression_analysis.ipynb)
* [Regression_Analysis](https://github.com/BenMcCright/Forecasting_Yen_Vs_USD/blob/master/Notebooks/regression_analysis.ipynb)
https://github.com/BenMcCright/Forecasting_Yen_Vs_USD/Notebooks/.git

## Time Series Models
![Yen Settle Price from 1990 to Present](Resources/yen_settle.png)
![Yen Settle vs. Trend from 2015 to present](Resources/settle_vs_trend.png)
![Yen Futures "Noise"](Resources/yen_noise.png)
![5 Day Returns Forecast - ARMA](Resources/yen_arma.png)
![5 Day Futures Price Forecast - ARIMA](Resources/yen_arima.png)
![5 Day Volatility Forecast - GARCH](Resources/yen_garch.png)
---
## Time Series Conclusions
### I would not buy the Yen right now, but would try to buy the Yen when its actual price is below the trend.
### The risk of the Yen is expected to increase.
### Both the ARMA and ARIMA model do not provide statistically significant insight due to their high p-levels, however the GARCH model has a low enough p-score that it is statistically significant.
---
## Regression Analysis Models
![Yen Futures Predictions vs. Actual](Resources/Yen_Futures_Predictions_Vs_Actual.png)
![In-Sample Predictions vs. Actual](Resources/In_Sample_Predictions_vs_Actual.png)
---
## Regression Analysis Conclusions
### The In-Sample predictions and Out-of-Sample predictions are very close to one another, but the In-Sample predictions are slightly more accurate.
---
## Mean Squared Error (MSE)
### - In-Sample = 0.0263
### - Out-of-Sample = 0.0287

## Root Mean Squared Error (RMSE)
### - In-Sample = 0.1622
### - Out-of-Sample = 0.1693