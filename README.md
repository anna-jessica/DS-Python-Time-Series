# Data Science Certificate Program - Foundations Course - Assignment 3

Assignment tasks:
In this assignment you will conduct time series analysis of financial data.

Install the yfinance library if you don't already have it.

(2 points) Download the adjusted close prices for META, MMM, IBM and AMZN for the last 60 months. If you run into any issues downloading the data from online sources, you can use .csv files provided. This will not affect your grade for the assignment.

(3 points) Resample the data to get prices for the end of the business month. Select the Adjusted Close for each stock.

(3 points) Use the pandas autocorrelation_plot() function to plot the autocorrelation of the adjusted month-end close prices for each of the stocks.

Are they autocorrelated?
Provide short explanation.
(4 points)

Calculate the monthly returns for each stock using the "shift trick" explained in the lecture, using shift() function.
Use pandas autotocorrelation_plot() to plot the autocorrelation of the monthly returns.
Are the returns autocorrelated? Provide short explanation.
(3 points)

Combine all 4 time series (returns) into a single DataFrame,
Visualize the correlation between the returns of all pairs of stocks using a scatter plot matrix (use scatter_matrix() function from pandas.plotting).
Explain the results. Is there any correlation?
