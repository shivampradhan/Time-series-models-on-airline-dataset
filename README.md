<a name="br1"></a> 

## TIME SERIES ANALYSIS

• A time series is a sequence of measurements done over time, usually

obtained at equally spaced intervals, be it daily, monthly, quarterly or

yearly.

• *Time series* data: A set of observations on the values that a variable

takes at different times.

• Eg.

• Daily air temperature or monthly precipitation in Pune

• Daily closing stock prices



<a name="br2"></a> 

## Time series analysis Flow

Series Stationarity Identification

Time Series plot of the series

Check for possible outliers

Check for the existence of a trend or seasonality

## Remove the trend and the seasonal component to get **stationary** residuals

Estimation

MME,MLE

Validation

Normality of error terms

Independency of error terms

Constant error variance (Homoscedasticity)

## Forecasting

Exponential smoothing methods

Minimum MSE forecasting



<a name="br3"></a> 

### Stationarity

The basic idea of stationarity is that the

probability laws governing the process **do not**

change with time.



<a name="br4"></a> 

Stationarity check



<a name="br5"></a> 

Components of time series



<a name="br6"></a> 

Type of tends



<a name="br7"></a> 

Decomposition and Smoothing

Done by subtracting the trend estimates from the **series**.

Done by dividing the **series** by the trend values.



<a name="br8"></a> 

## Seasonality

•**Holt-Winter's Additive Method** − When the seasonality is additive in nature.

•**Holt-Winter’s Multiplicative Method** − When the seasonality is multiplicative in nature.



<a name="br9"></a> 

Exponential models based on error ,trend,

seasonality decomposition

Eg. (“MAM”)multiplicative error, additive trend, and multiplicative seasonality



<a name="br10"></a> 

## AR ,MA Modelling

the output variable depends [linearly](https://en.wikipedia.org/wiki/Linear_prediction)[ ](https://en.wikipedia.org/wiki/Linear_prediction)on its own previous values and on a [stochastic](https://en.wikipedia.org/wiki/Stochastic_variable)[ ](https://en.wikipedia.org/wiki/Stochastic_variable)term

output variable depends [linearly](https://en.wikipedia.org/wiki/Linear_prediction)[ ](https://en.wikipedia.org/wiki/Linear_prediction)on the current and various past values of a [stochastic](https://en.wikipedia.org/wiki/Stochastic)[ ](https://en.wikipedia.org/wiki/Stochastic)term.



<a name="br11"></a> 

Different models



<a name="br12"></a> 

Finding right model



<a name="br13"></a> 

Model selection using ACF PCF



<a name="br14"></a> 

ACF and PACF plot



<a name="br15"></a> 

Arima Model

Auto Arima finds the values of P d Q automatically within a range of values



<a name="br16"></a> 

ARIMA for seasonal data



<a name="br17"></a> 

Limitations

• They require lots of data

• Some missing values can really effect the model

• They assumes a Linear Relationship

• Usually deals with univariate data

• Not good when dataset have multiple inputs



<a name="br18"></a> 

Recap (1)



<a name="br19"></a> 

Recap (2)

