# breakout_strategy
These strategies are designed to pursue stocks that are surging beyond their normal moving average, and therefore likely to continue 
increasing in value

Our first strategy published here uses a threshold of the average highs from the previous 25 days and 1/3 of the stock ATR; the long signal
is triggered at that point, while a short signal is triggered by going below the average low minus 1/3 of stock ATR. Stocks are then sold
if they either drop below the average high or go above the average low, or at the end of the day. These are all variables to be 
experimented with to determine which are the most successful.
