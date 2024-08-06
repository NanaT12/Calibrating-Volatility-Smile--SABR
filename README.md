# Calibrating-Volatility-Smile--SABR
This project focuses on using the Stochastic Alpha Beta Rho (SABR) model, developed in 2002, for modeling derivatives. The SABR model is particularly effective at capturing observed market anomalies such as the volatility smile or skew.

Overview
The SABR model is a popular choice for modeling the dynamics of implied volatility surfaces for options. It allows for more accurate pricing and risk management of derivatives compared to models with constant volatility.

Key Features of the SABR Model
Stochastic Volatility: The model incorporates stochastic volatility, making it more realistic for capturing the behavior of options.
Elasticity Parameter (Beta): Allows the model to interpolate between different types of price processes.
Correlation (Rho): Captures the correlation between the asset price and its volatility, allowing for modeling skewness in implied volatility.
Conditions for Using the SABR Model
Prices follow a geometric Brownian motion: This means the asset prices are assumed to follow a lognormal distribution.
Volatility follows an Ornstein-Uhlenbeck process: Volatility is mean-reverting, preventing it from drifting indefinitely.
