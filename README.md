# stock_market
In this project I have predicted next week closing price of a stock using stock open/high/low/close/volume.

The stock used in this project is deepak nitrite (NSE). Previous 11 year data is used to train the model.  

The data is downloaded from yahoo finance and the data only contains open/high/low/close/volume data.

The remaining columns are created using these pre-availble columns. 

Artificially created columns include technical tools such as relative strength index, moving average etc. 

The project uses linear regression, ridge regression, lasso regression and random forest models.  Out of all random forest performs good. 
Min error in prediction: 4 %
Max error in prediction: 12%

