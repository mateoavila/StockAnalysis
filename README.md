# StockAnalysis

## Overall Idea
I will use the basic idea of buy low sell high 

in order to do that I will get the average closing price from the last 100 days, the last 30 days and last day on the market. I will use these 3 data points as markers to see how the stock is doing.

There are 3 possible outcomes:

- If the 100 day average is greater than the 30 day average I assume it will go up and I will buy when it is low
- If the 100 day average is lower than the 30 day average and the last days closing price was up I assume it is too high and the stock will come down so I will sell high
- If the 30 day average is higher than the 100 day average but the last day was below the 30 day average I cant conclude much so I will either hold if i have it or wait another day.
    
    
### week 2

I changed my analysis section of my code to work off points now. 
- If the 100 day average is higher than the month average I give the stock a point otherwise I take a point away.
- if the last day is lower than the month average I give the stock a point otherwise I take a point away.
- if the stock grew last year within this month I give the stock a point otherwise I take a point way.
- if the points are positive I buy if they are negative I sell if they are nutural I do nothing.

I am also taking into consideration Walmart stock

### week 3
I added more criteria to my analysis now: 
- I take into consideration 2 and 3 years ago from t
- if this month from 1 2 and 3 years ago all ended higher than it started I give 2 points because there is reliable data to show that at this time the stock goes up.

### week 4
I took a look into major factors that people look at when trying to determing good stocks. This week I added more data to my data collected by comparing the 5 day hisory of the stock while still keeping my mentality of buying low and selling high. I added more point criteria based on this addition of ananysis. 
