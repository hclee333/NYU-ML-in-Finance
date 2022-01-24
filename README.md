# NYU-ML-in-Finance

(A) pca_eigen_portfolios : Contains Python Code using PCA in tensorflow to build eigen portfolios from historic SnP500 time series data.
NYU Fundamentals of ML Week 4_sbsorp_ratio contains Python Code using PCA and LinearAutoEncoder in tensorflow to formulate a simple trading strategy. 
Trading Strategy is based on absorption ratio of historic SnP500 time series data and using that to adjust deltas in a portfolio. 
Portfolio is classified into two types of stocks : Fixed Income (or Value) and Equity (or Growth) and only two deltas.
Exponential Weighted Returns should be used instead of Equally Weighted Returns to improve performance of Trading Strategy. 
In reality, more recent price movements have greater effect on current price than price movements in the distant past. 
(B) discrete_black_scholes : Simulate the Black Scholes Model in Discrete Time and obtain the option premium and option greeks
(C) Pairs Trading :  uses basic ML (not RL) to set buy and sell levels for individual stocks in a strategy that is common among hedge funds - Pair Trading.  Historic data is available from Yahoo Finance.
