# Udacity-AI4Trading-BreakoutStrategy
## Project 2 Breakout Strategy

This notebook is part of the Udacity Nano Degree - AI for Trading

It works through loading Market Data and several of the techniques involved in analysing stock.

## Including

1 - Computing Highs and Lows for the close price within a given window (days).

2 - Computing Long and Short Signals (i.e. when to buy and sell stock).  This was then further refined to consider the signals over a certain period of time, i.e. more than one day as defined by the trader.

3 - Once the trading signal is defined, we then explore how long to short or long the stock.  And then explore log returns over this time frame.

4 - With the trading signal and projected returns, we then explore what the likely return would be based on there being a present signal.  The signal is 1, -1 or 0 depending on whether we are shorting, longing or doing nothing.  Multiplying these out gives the projected returns.

5 - From here we can explore the most promising look ahead range to give the larger yield for the portfolio.

6 - Outliers are then explored to see how they impact the performance of the trading strategy for the portfolio.  Here the Kolmogorov-Smirnov test (KS test) is used.
