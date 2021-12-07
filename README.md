# ADS506

Time Series Analysis of Zillow's Home Value Zestimate®:
Predicting the Log Error of Zestimate® values

Team Members:
Roberto Cancel
Tyler Wolff
Kiran Singh

Data Source: https://www.kaggle.com/c/zillow-prize-1/overview

Zillow.com is the United States' most visited real estate website – offering customers a wide 
range of real estate services, including its proprietary Zestimate®. Real estate professionals and 
homeowners have scrutinized Zillow's Zestimates® due to inaccuracies since they heavily depend on the 
amount, recency, and accuracy of the data provided for each market and property. The Zillow Prize 
competition was launched to help Zillow decrease the log error of Zestimates®, which, at the time of the 
contest, was 4.5% nationwide - larger error rates exist in certain markets. Our project aims to predict 
the log error of Zillow's Zestimates using various time series forecasting models for Los Angeles, Orange, 
and Ventura, California. Since we decided to include housing features in our model, an extensive data 
wrangling process was conducted to remove our dataset's millions of missing data points. A minimum 
missingness threshold of five percent was established and greatly reduced the missingness. Complete 
Case analysis was used to rationalize the remaining missingness. Three models were developed: OLS, 
SES, and ARIMA. The ARIMA (3,0,0) or AR(3) model resulted in the lowest MAE of 0.0123, the Kaggle 
competition criterion for model selection. Predictions of October, November, and December 2017 log 
errors were made using the ARIMA (3,0,0), and the values within the 95% confidence interval were 
within the range of previous values. Our data was the best fit to an AR(3) model indicates that predicted 
values are based on the past three values of log error.
