# Pricing-a-Garch-model

We consider a GARCH model without risk premium (λ = 0 with the notation used in the course).

Make a program to compute the price of a Call option using a GARCH Model. Use a Monte Carlo method to evaluate the expectation with respect to the law of the GARCH process. For the calibration of the GARCH model, one can used typical values of the parameters for financial data on a daily scale (it is not asked to estimate the model on real data). 
For the time to expiration date, you may choose T ' 250, corresponding to one year.

Numerically study how the price the option depends on the value of the ratio S/K, where S is the price of the underlying asset at time 0 and K is the strike price of the option (the ratio S/K could range from 0.5 to 2).

Finally, compute the values of the implied volatility for the different values of the moneyness S/K.
