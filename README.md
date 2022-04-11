# stock_market
In this project I have predicted next week closing price of a stock using previous 6 days data such as open/high/low/close/volume.

The stock used in this project is deepak nitrite (NSE). Previous 11 year data is used to train the model.  

The data is downloaded from yahoo finance and the data only contains open/high/low/close/volume data.

The remaining columns are created using these pre-availble columns. 

Artificially created columns include previous 6 day open/high/low/close, %change in price of previous 6 days and some technical tools such as relative strength index, moving average etc. 


In the latest update of the project 5 more files are added on git. The changes made to new files are the features addition (Many technical analysis points are added in newer update.)

Out of 5 new files 1 is regression model of the project which predicts the stock price for the next week rather than immidiate day because noise in the market may ruin the performance of the model hence prediction of next week can be made more accurately.

The other 4 new files use classification model for the same project but the bullishness or bearishness is divided in 5/4/3/2 parts in various models.

When there are 5  class (Very bullish / very bearish / bullish / bearish and neutral) the overall accuracy is 70%

When there are 4  class (Very bullish / very bearish / bullish / bearish ) the overall accuracy is 70%

When there are 3  class (bullish / bearish and neutral) the overall accuracy is 76%

When there are 2  class (bullish / bearish ) the overall accuracy is 85%

It seems the simple the model targets better the acccuracy that we get.
