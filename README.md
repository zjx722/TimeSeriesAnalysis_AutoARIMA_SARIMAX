# TimeSeriesAnalysis_AutoARIMA_SARIMAX
### Project description:

In this notebook, we will explore two time series models to fit our current daily price data and make predictions based on our fitted models. The first method is **Auto-ARIMA** model, the second one is **SARIMAX** model. 

The advantage of the first model is that it can provide a stationary series using ADF test, the disadvantage is complicated data manipulation, for example: taking difference, cut-off partial series etc.

The advantage of the second mode is that it can deal with the original dataset and capture the trend and seasonality directly. **Statistical results show that the second model is more suitable to forecast the current dataset and can be easily generalized to a larger dataset.**
