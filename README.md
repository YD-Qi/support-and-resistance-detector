# Purpose:

This notebook is intended to scan all crypto from Bianace and calculate their support and resistance levels, ideally, combined with pinbar detections to generate long/short signals.

But the ploting results are too large to be uploaded to github, so in the code I end up with only scan three coins and the detected levels are not combined with pinbar signals yet.

I will make anothe noebook where you may enter any crypto to get its support and resistance levels and plot the results.

# How it works:

This program downloads most recent market data from Binance. 

Then for each coin, support and resistance levels are calculated, printed and ploted.

I utilize two ways to detect levels.

* First, fractual method.

**A fractal is a candlestick pattern made by 5 candles. 
The third candle has the lowest low price, the previous candles have decreasing 
lows and the next candles have increasing lows. By this pattern, 
the low of the third candle is the support level. 
The same concept applies to resistance levels, 
where the third candle has the highest high of the five ones.**

See more details about this method at https://towardsdatascience.com/detection-of-price-support-and-resistance-levels-in-python-baedc44c34c9

* Second, argrelextrema method. It is from from scipy package to detect lowest and highest values in a local area as support and resistance levels.

Both methods works well.

