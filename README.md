# Stocks-Responsiveness
## MA thesis
Research question: How has passive investing affected stock responsiveness to news.

## Data
Using CRSP data to identify index funds, LSEG data to get funds' stock holdings, CRSP data for stock returns, LSEG IBES data for earnings dates.

## Current Problems
Some stocks (442 out of 7430) have a passive share greater than qual to 1, maybe drop them?

## Next Potential Steps
1. Clean notebook, get rid of initial_stuff and 13f data
2. Merge earnings and change date formats to days from/to earinings.
3. Analysis stock by stock high vs low passive ownership high vs low median, daily volatility etc.