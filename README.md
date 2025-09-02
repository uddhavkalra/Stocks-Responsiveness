# Stocks-Responsiveness
## MA thesis
Research question: How has passive investing affected stock responsiveness to news.

## Data
Currently using SEC data for funds, total assets and 13f filings data and CUSIP-ticker data from yoshishima's github. Only used 13f filings data from 2025 March April May will add more quarters once resolve problems. With CRSP data will not need CUSIP-ticker data so will change code and drop that dataset.

## Current Problems
Ammendents: Either New Holdings or Restatements, if they are restatments and have the same reporting date and ammendement number which one to use.
Pitential Priority: If New Holdings and ammend number is the same add all, if restatements: Take highest ammend number, if missing or multiple take the highest shares number. (Highest ammend number will obviously take priority)

## Next Potential Steps
1. Implement the potential solution above
2. Clean notebook
3. Merge stock data and identify passive funds
4. Get events data
5. Analysis