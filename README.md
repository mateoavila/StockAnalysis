# StockAnalysis

Overall Idea

I will use the basic idea of buy low sell high

in order to do that I will get the average closing price from the last 100 days, the last 30 days and last day on the market. I will use these 3 data points as markers to see how the stock is doing.

There are 3 possible outcomes:

-If the 100 day average is greater than the 30 day average I assume it will go up and I will buy when it is low
-If the 100 day average is lower than the 30 day average and the last days closing price was up I assume it is too high and the stock will come down so I will sell high
-If the 30 day average is higher than the 100 day average but the last day was below the 30 day average I cant conclude much so I will either hold if i have it or wait another day.
