# support-and-resistance-detector

This program downloads most recent market data from Binance. 

Then for each coin, support and resistance levels are calculated, printed and ploted.

Currently, the levels are computed with fractual method.

**A fractal is a candlestick pattern made by 5 candles. 
The third candle has the lowest low price, the previous candles have decreasing 
lows and the next candles have increasing lows. By this pattern, 
the low of the third candle is the support level. 
The same concept applies to resistance levels, 
where the third candle has the highest high of the five ones.**

See more details about this method at https://towardsdatascience.com/detection-of-price-support-and-resistance-levels-in-python-baedc44c34c9
