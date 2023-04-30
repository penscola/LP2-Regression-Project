# Time-series-analysis-and-forecasting
In this repository, I have shared project files in time-series analysis and forecasting domain.

- Project : time-series-analysis-methods - This file contains methods and techniques that are used in time-series forecasting and analysis.

## Background
- This is a time series analysis & forecasting problem. In this project, we shalll predict store sales on data from Corporation Favorita, a large Ecuadorian-based grocery retailer.

- Specifically, we are to build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores.

- The training data includes dates, store, and product information, whether that item was being promoted, as well as the sales numbers. Additional files include supplementary information that may be useful in building your models

We have different data sets to our disposal:

- holiday_events: a list with all ecuadorian holidays and events;
- oil: a list of oilprices meant to serve as an economic indicator of Ecuador;
- stores: a dataset with information about our stores: includes city, state, type and others;
- transactions: a dataset containing the number of aggregated transactions for each store on each day;
- test: general testset of 16 days of sales we will need to predict;
- train: a huge trainset with about 4 years of data to predict our test sales data.

## Objectives and tasks
Prepare S&P 500 stocks data to find TOP 10 most traded stocks
Analyse stock data to find best performing stocks and recommend which stocks to buy
Conduct statistical hypothesis test to prove daily return stock hyppthesis
Build forecasting models to find forecast future values of stock ticker 'FB' and 'AAPL'

## Approch and techniques
- Used for loops and dataframe filtering to find TOP 10 traded stocks
- Analysed top 10 stocks to find average trade volume, growth of stocks
- Did comprative anaalysis of 7 tech stocks
- 1 sample t-test to prove hypothesis of daily return being 0%
- technical analysis using moving average method and candle stick charts
- Built forecasting models using FB's Prophet module and also using Auto-ARIMA models.

## Learnings from this project
- Learned how to comprehensively analyze stock price data to find relevant insights
- technical analysis of stocks using comparative analysis, moving average and candlestick charts
- time-series forecast modelling using auto-ARIMA models, evaluation metric RMSE, non-stationarity of 
- time-series and ACF/PACF plots

## Tools/technologies used
Python
fbprophet
pmdarima
matplotlib
pandas
plotly
statsmodels
mplfinance