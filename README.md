# Opening-Momentum-Strategy
When a stock gaps up on good news, a momentum strategy is most natural, but entries, exits, and position sizing ultimately determine the return and win rate.  

We will back test on 3 years worth of seconds level data and use the most recent 2 years as the test set(check how the strategy generalizes)

The setup we are trying to back test:

1. The stock opens higher than previous days' high, opening price >= previous close + (ADR of previous 5 days)
2. The first 2 min volume is 3 standard deviations away from the mean of the previous 20 days volume
3. Ideally there is no resistance level sitting above the open.

The idea behind this setup: 
1. For a genuine catalyst for the stock, it should be a suprise to the market, which explains the aggresive repricing of the stock during pre-market.
2. If the catalyst attracts attention, its traded volume should be high.
3. When there are sellers waiting above, there could be downward pressure on the stock. We could also set take profit to be the resistance level. 
            
The goal is to understand the typical behavior of the stock price evolution under this set up, and from there we can develop entries, exits and position sizing. 




