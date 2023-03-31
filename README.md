# Google Stock Market Prediction

## What is a time series and why analyse it?

Time series is a sequence of observations recorded at regular intervals of time. For example, daily stock prices, energy/ water consumption, traffic flow in major highways, retail demand etc. Time series analysis provides insights like seasonal patterns, trends and demand forecasting that can help maximize the profits.

### Get the stock price data using finance API:
Yahoo finance is one of the most popular websites to get stock data. In order to get real time data we collect the stock data using the yfinance API. 
You can install yfinance by using pip in your terminal as follows:

Pip install yfinance

The we extract last one year of data.

![My Image](img1.JPG)

There are no null or missing values in the dataset so we move to visualisations.
We use various charts such as candlestick chart, bar chart and rangeslider to visualize the data.

![Candlestick Chart](candlestick.JPG)
