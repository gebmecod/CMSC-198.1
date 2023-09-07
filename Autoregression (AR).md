**uses observations from previous time steps as input to a regression equation to predict the value at the next time step**.

A model is said to be autoregressive if its prediction value is based from the past lags(previous value) that has direct correlation with the present value.

PACF is commonly used to determine the significant lags within the time series.

Autoregressive model states that,
	$a_t = \theta_0 a_t + \theta_1 a_{t-1} + ... + \theta_q a_{t-q}$ , where $a_t$ is the predicted 


