
# Time Series Analysis📈📊

**Definition**
- sequence of data taken at equally spaced intervals (can be hourly, daily, weekly, monthly, and quarterly)
- a process of using statistical model to predict future values of a time series based on past values

 **Terminologies:**
1. ***Trend***: increasing and decreasing of a series overtime. Can be increasing, decreasing, or stationary.
2. ***Seasonality***: the repeating patterns or cycles of behavior overtime.
3. ***ETS (Error, Trend, Seasonality) Decomposition***: used to separate components of time series.
4. ***Stationarity***: shows the mean value of the series that remains constant over the time period.
5. ***Differencing***: used to make the series stationary and to control the auto-correlations.
6. ***Dependence***: association of two observations of the same variable at prior time periods.
7. ***Noise***: The variability in the observations that cannot be explained by the model.

**Smoothing Techniques**
	*Essential to reduce noise present in our series and point out the true patterns that may present over time.*

**Types of Smoothing Techniques**:
1. Single Exponential Smoothing (SES)
	- is a time series forecasting method for univariate data without trend or seasonality
2. Double Exponential Smoothing
3. Triple Exponential Smoothing

## Forecasting Models

**[[Autoregression (AR)]]**
- models the next step in the sequence as a linear function of the observation at prior time steps.
- suitable for univariate time series without trend and seasonal components.

**[[Moving Average]]**
- used to analyze the time-series data by calculating averages of different subsets of the complete dataset.
- also called moving mean or rolling mean.

**[[Autoregressive Moving Average]]**
- models the next step in the sequence as a linear function of the observations and residual errors at prior time steps. Combines AR and MA

**[[Autoregressive Integrated Moving Average]]**
- models the next step in the sequence as a linear function of the differenced observations and residual errors at prior time steps.
- combines both AR and MA as well as a differencing pre-processing step of the sequence to make the sequence stationary, called *integration* (I)