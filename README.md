# NYU-ML-in-Finance
NYU ML in Finance
pca_eigen_portfolios contains Python Code using PCA in tensorflow to build eigen portfolios from historic SnP500 time series data.
NYU Fundamentals of ML Week 4_sbsorp_ratio contains Python Code using PCA and LinearAutoEncoder in tensorflow to formulate a simple trading strategy. 
Trading Strategy is based on absorption ratio of historic SnP500 time series data and using that to adjust deltas in a portfolio. 
Portfolio is classified into two types of stocks : Fixed Income (or Value) and Equity (or Growth) and only two deltas.
Exponential Weighted Returns should be used instead of Equally Weighted Returns to improve performance of Trading Strategy. 
In reality, more recent price movements have greater effect on current price than price movements in the distant past. 
