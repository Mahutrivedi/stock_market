# stock_market
In this project I have predicted next day closing price of a stock using previous 6 days data such as open/high/low/close/volume.

The stock used in this project is deepak nitrite (NSE). Previous 5 year data is used to train the model.  

The data is downloaded from yahoo finance and the data only contains open/high/low/close/volume data.

The remaining columns are created using these pre-availble columns. 

Artificially created columns include previous 6 day open/high/low/close, %change in price of previous 6 days and some technical tools such as relative strength index, moving average etc. 


In the latest update of the project 5 more files are added on git. 
The changes made to new files are the features addition (Many technical analysis points are added in newer update.)
Out of 5 new files 1 is regression model of the project which predicts the stock price for the next week rather than immidiate day because noise in the market may ruin the performance of the model hence prediction of next can be made more accurately.
