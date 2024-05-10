This project deals with temperature forecasting influenced by CO2 levels. The notebook is designed to use important python libraries for data processing and visualization, which can help to examine CO2 and temperature datasets. Using Augmented Dickey-Fuller and KPSS tests, the stationarity of the data is confirmed, so that the ARIMA and SARIMA models are fitted with auto_arima.

The study uses CO2 as an exogenous variable to improve model predictions about it while using metrics like MAE and MSE to assess accuracy. Additionally, Facebook’s prophet approach is applied due to its ability to handle seasonality effectively. Matplotlib and Plotly are used in visualizing results as well as comparing forecasts against actuals.

Finally, this analysis sums up on how well these models performed as well as what could be done differently in future when dealing with environmental data forecas

Reference:https://doi.org/10.1175/WAF-D-19-0158.1