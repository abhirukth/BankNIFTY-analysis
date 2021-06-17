# BankNIFTY-analysis

## Tasks : 

-	Attached Bank Nifty time series data of 5 min.
-	Backtest using Python.
-	Convert data into 15 min time frame.
  
- Intraday trades are to be taken and mandatorily closed in the same day.
- Trade starts only after 2nd 15-minute candle (9:30 to 9:45)
  	
- If candle closes above VWAP, we will buy and if candle closes below VWAP, we will sell
-	Example: If 2nd candle is closing above VWAP, we will buy 1 tick above candle high and Stop Loss (SL) will be 1 tick below candle low.
  
- If stop loss is not hit, then all trades are exited at 3:15 PM.


-	Calculate the overall profit and loss. 
-	Segregate the Profit and Loss Year wise and Day wise
-	Suggest best performing Year.
