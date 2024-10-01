# This is a collection of trading strategy tryouts.
## A. Pair Trading for cancelling out risks with two (possibly) cointegrated targets (bonds, indices, stocks, commodities...)
1. 10yr-30yr T-bonds spread strategies
2. AAPL-MSFT spread strategies

Here the static beta coefficients are tried, where in the T-bond case, it works out, but not for the AAPL-MSFT demo as the residual is not stationary.
The alternative (and also really cool) idea is the usage of kalman filter to dynamically update the beta coefficient between the two items.

Notes: AAPL-MSFT demo has the cumulative profit shown as it is easier to evaluate with stock prices. 
