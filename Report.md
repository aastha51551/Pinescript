# Report [SoC 2023]

<p align="center"> Developing trading strategies with PineScript </p>

<p align="center"> Astha Sahu </p>

<p align="center"> Mentored by - Vivek kumar and Rajik Kumar </p>

## About the Project
In this project, we learnt developing trading strategies using pine script on TradingView platform. We learnt about various indicators, signals and strategies . We also learnt about importance of time frame. In the end, I was able to develope my own strategy and test them sucessfully on different stocks and index. Given below are some the indicators, signals and strategies that I have tested during this project.

### EMA 21 and SMA 21 Combine

EMA stands for Exponential Moving Average and SMA stands for Simple Moving Average. In this section, I plotted two graphs and overlayed them on the candlestick chart. Click on this [link](EMA-21-SMA-21-combine) to view the code.

### MACD

The moving average convergence/divergence (MACD, or MAC-D) line is calculated by 
subtracting the 26-period exponential moving average (EMA) from the 12-period EMA. 
The signal line is a nine-period EMA of the MACD line.
MACD triggers technical signals when the MACD line crosses above the signal line (to buy) 
or falls below it (to sell).Click on this [link](MACD) to view the code.

### Bollinger Bands

Three lines compose Bollinger Bands: A simple moving average, or the middle band, 
and an upper and lower band. The upper and lower bands are typically +/-2 standard deviations
from a 20-day simple moving average and can be modified.
When the price continually touches the upper Bollinger Band, it can indicate an overbought signal.
If the price continually touches the lower band it can indicate an oversold signal.Click on this [link](Bollinger-Bands) to view the code.

### Dead Crossover

It happens when a 200 day sma crosses above a 50 day sma.
It’s a sign that the market has deteriorated in a period little longer than 2 months.
Click on this [link](Dead-Crossover) to view the code.

### Intraday

In Intraday Strategy , we buy and sell within the same day.Click on this [link](Intraday) to view the code.

### Inside Candle Signal

It is a signal. When the opening and closing value of the current candle falls within the range of opening 
and closing values of the previous candle, it’s called as an inside candle. Click on this [link](Inside-Candle.txt) to view the code.

### Doji

Doji is a candlestick pattern in which the opening and the closing price for a security is the same.
It usually signals a trend reversal. Click on this [link](Doji.txt) to view the code.

### Monthly Closing Strategy

It generates buy signals if the closing price is higher than the previous month's closing price and sell signals if the closing price is lower than the previous month's closing price.  Click on this [link](Monthly-closing-strategy) to view the code.

### Bollinger Band Strategy

A Bollinger Bands strategy is a popular technical analysis approach that uses Bollinger Bands, which consist of a middle (typically a simple moving average) band and two outer bands that represent standard deviations of the middle band. The strategy involves generating buy and sell signals based on the price crossing the bands and potentially using other indicators to confirm the signals.  Click on this [link](Bollinger-Band-Strategy) to view the code.

### 5 EMA Strategy

In this a buy signal is generated when close crosses over 5 period EMA and sell signal when it crosses under.  Click on this [link](5-EMA-Strategy) to view the code.

### My Strategy 1 (ATR EMA Strategy)

In the strategy , we enter a long position when closing price crosses over EMA such that closing price is 2 times ATR above EMA.
We exit the long position when closing price crosses below EMA. Click on this [link](ATR-EMA-Strategy-(mystrategy1)) to view the code.

### My Strategy 2 ( Momentum Strategy)

In his strategy we use the comcept of momentum and fast and slow moving averages. Fast moving averages have shorter SMA period as compared to slow moving averages.  Click on this [link](Momentum-Strategy(myStrategy2)) to view the code.


