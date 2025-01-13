# Project proposal for Predictive Stock Price Model
Author: Sarang Kumar Maheshwari

## 1. Why: Question/Topic being investigated 1pt
I want to design a program that allows a day trader in the stock market to easily and with some confidence be able to predict the stock price for the next minute.
Such a tool should be simple to design as we are interested in predicting only price of the commodity in a very short term timeframe. 
In addition, such a tool would give confidence in buying stocks easily and remove the guesswork/research required in buying a stock.
This will be a useful tool for day-traders who are rapidly buying and selling stock multiple times throughout the day.

## 2. How: Plan of attack 1pt
I will use multiple online resources that talks about predictive analytics using machine learning to use a simple ARIMA model (as the data is in TimeSeries)
that can be used to forecast stock price. Stock price for that day will be imported using API call to yahoo finance and the 'Low' price will be investigated. 
The ARIMA model will predict the next price. 
Thought outside scope of this project, the next step will be to connect this model to a brokerage and automatically execute a Buy Order for the stock if the predicted price is lower than current.


## 3. What: Dataset, models, framework, components 2pts
Data from YFinance
Pandas Datetime
Guide to ARIMA model: https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/
Reference Article: https://towardsdatascience.com/time-series-forecasting-predicting-stock-prices-using-an-arima-model-2e3b3080bd70

