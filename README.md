# Option Pricing Models

## Introduction : This repository represents a simple program to calculate the options prices and the option greeks using the Black-Scholes model.    


## Some assumptions in the Black-Scholes Model

- Call/Put option price is calculated with following assumptions:
- European option can be exercised only on maturity date.
- Underlying stock does not pay divident during option's lifetime.  
- The risk free rate and volatility are constant.
- Efficient Market Hypothesis - market movements cannot be predicted.
- Lognormal distribution of underlying returns.


## Some parameters that we will set for the Black-Scholes Model


- Ticker  
- Strike price  
- Expiry date  
- Risk-free rate  
- Volatility  


Option pricing models are implemented in [Python 3.7](https://www.python.org/downloads/release/python-377/). 
Latest spot price, for specified ticker, is fetched from Yahoo Finance API using [pandas-datareader](https://pandas-datareader.readthedocs.io/en/latest/). 

## How to run code?
You can just copy paste the code in any IDE and it should run just fine.
