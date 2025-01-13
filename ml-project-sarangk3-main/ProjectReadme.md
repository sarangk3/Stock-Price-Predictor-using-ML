Here is where you include:
  - Background on your code files
	There is one .ipynb notebook that be opened and all cells runned, without additional need for anything.
	User specifications:
	1. Can manually enter the Stock ticker symbol of interest. Currently it is set to 'TSLA' for Tesla company stock
	2. There is a plot for train/test data of stock price varying throughout day. 
		Note: The X-axis will have more data points the later in the day this file is run (as it is retreiving stock price information for the current day)
		If this file is run early in the morning or on a weekend, there may not be much data available as the exchange opens at 9:30AM EST everyday and closed on weekends.
			
  - How to run your code, guide to install any additional packages
	Easiest way is to run all cells one after the other. The installs required are the following:
	yfinance, pandas, matplotlib, datetime, ARIMA, mean_squared_error
	Note: All of these have commands within the file to be installed so user does not require any action.
	
  - Results, interpretation and reflection
	Note: More results analysis are done in the .ipynb file itself. Here is an overview:
	I was always interested in using code to run a predictive stock price model using some sort of AI. 
	This class project was a phenomenal example of being able to do so.
	There is only one value being predicted (y_test[0]) which is the prediction for price of stock at the next minute.
	If the prediction is greater than the last defined price, then a buy order can be placed. 
	Next step is to connect to a broker using API call and automatically buy if the predicted price is lower than current. 
	In addition, a WhatsApp or Telegram message could be sent using a bot to notify the user of the purchase order. 
	I will be doing this on my own time as it will involve security credentials being shown, but am excited to get underway
