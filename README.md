# VaR-Calculation

Value at Risk: The most that anyone can lose on its investments; specified with three parameters: level of loss, time period, confidence level. 
In other words, Value-at-risk is a statistical measure of the riskiness of financial entities or portfolios of assets.

It is defined as the maximum dollar amount expected to be lost over a given time horizon, at a pre-defined confidence level. 
For example, if the 95% one-month VAR is $1 million, there is 95% confidence that over the next month the portfolio will not lose more than $1 million.

It can be calculated using different techniques: 
1. Under the parametric method, also known as variance-covariance method, VAR is calculated as a function of mean and variance of the returns series, assuming normal distribution. 
2. With the historical method, VAR is determined by taking the returns belonging to the lowest quintile of the series (identified by the confidence level) and observing the highest of those returns. 
3. The Monte Carlo method simulates large numbers of scenarios for the portfolio and determines VAR by observing the distribution of the resulting paths.

Drawbacks:
1. Unable to measure Potential loss associated with the tail of the probability distribution out of the confidence level
2. Not additive, so VAR figures of components of a portfolio do not add to the VAR of the overall portfolio, because this measure does not take correlations into account and a simple addition could lead to double counting

Codes are available in the repository to measure VaR of the portfolio using different techniques.
