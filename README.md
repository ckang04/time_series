# Summary & Conclusions

In the present study, a time series analysis is conducted in order to determine any predictable behavior in the Dollar-Yen exchange rate futures. To begin, we pulled historical daily Yen futures starting from January 1, 1990 up to the present (2020). The collected data was plotted and the Settle price was decomposed into a trend and noise using a Hodrick-Prescott Filter. We then applied the ARMA model and ARIMA model in order to forecast returns and our findings are as follows:

1. **Based on your time series analysis, would you buy the Yen now?** Our answer is inconclusive due to the conflicting information found in the results. The ARMA model had a lower AIC and BIC (15798.142, 15832.765 respectively), which were slightly lower than ARIMA. However, the ARIMA model demonstrated to be a better fit with 0.302, versus 0.422. The two models predict that the price of Yen futures will move in opposite directions from each other, hence a confident recommendation cannot be made at this time. 

2. **Is the risk of the Yen expected to increase or decrease?** Based on the GARCH analysis, the risk of Yen is expected to increase (see the last chart on time_series ipynb file).

3. **Based on the model evaluation, would you feel confident in using these models for trading?** In addition to the fact that volatility is expected to increase, I would not use these models for trading based on the model fit assessment. 
