# CVAR_analysis

Conditional Value at Risk Analysis

Shows the basic value at risk (VAR) and conditional value at risk (CVAR) analysis on [yfinance](https://pypi.org/project/yfinance/) collected data using Python.

`VAR` is a method used to measure the maximum potential losses that a company or an investment could experience over a certain time period, with a specified level of confidence.

`CVAR` (aka the expected shortfall) is a risk measure of the expected loss beyond the VAR level. It estimates the expected loss given that the loss exceeds the VAR level.

In practice, there are 3 main approaches to compute the VAR and CVAR, namely historical method, parametric method (variance-covariance), or Monte Carlo simulation. They are all widely used in portfolio and risk management.
