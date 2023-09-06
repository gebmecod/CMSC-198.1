**uses observations from previous time steps as input to a regression equation to predict the value at the next time step**.

A model is said to be autoregressive if its prediction value is based from the past lags(previous value) that has direct correlation with the present value.

PACF is commonly used to determine the significant lags within the time series.

$a_t = a_t + \theta_{t-1} + ... + \theta_{t-q}

