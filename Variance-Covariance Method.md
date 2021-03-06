The variance-covariance method is an analytical way to calculate VaR.

Limitations: It is assumed that the growth in the value of all risk factors of a bank portfolio is a normal distribution and that the changes in portfolio value, with the exception of option instruments, depend linearly on the changes of these risk factors.

It is designed for portfolios where there is a linear relationship between risk and portfolio positions. Consequently, it can break down when the portfolio includes options, since the payoffs on an option are not linear

Conventional estimates of VaR are based upon the assumption that the standard deviation in returns does not change over time (homoskedasticity)
Suggestion: two variants – Autoregressive Conditional Heteroskedasticity (ARCH) and Generalized Autoregressive Conditional Heteroskedasticity (GARCH) – that provide better forecasts of variance and, by extension, better measures of Value at Risk.


Note: norm.ppf() takes a percentage and returns a standard deviation multiplier for what value that percentage occurs at.
