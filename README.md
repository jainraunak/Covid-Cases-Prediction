# Covid Cases Prediction

Covid cases prediction has become an important tool in today's world. If we are able to predict covid cases accurately, then we will be prepared well in advance for the outcome. So, I have tried to predict covid cases for California state. The covid cases data can be found <a href = "https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-states.csv">here</a>.

I have used time series models like **ARIMA**, **SARIMA** and **Holt Winters** to predict covid cases and have used **Thymeboost** for outlier detection.

For ARIMA and SARIMA model, we require time series to be stationary and so, I have used **ADF Test** to check stationarity of time series. 

In ARIMA model, we need to find the best **Auto Regressive** and **Moving Average** term. So, I have used **ACF and PACF plots** to find best Auto Regressive and Moving Average term.

A good time series model has uncorrelated residuals and to analyse residuals correlation, I have used **Durbin Watson test**.
