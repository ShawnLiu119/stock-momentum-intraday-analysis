# stock-momentum-intraday-analysis
analyze intraday momentum reversal signal of stock market 

#### data access limitation by API <Br>
1. yfinance: not official, access seems to be blocked by yahoo finance <br>
2. finnhub: allow more requests per min, but its free tier limits to access AAPL ticker, not open for ETF like QQQ or SPY. The paid premier tier does offer <br>
3. alpha-vantage: same as finnhub, free API does not offer access to ETF like QQQ or SPY but open for stock like MSFT or AAPL <br>
4. polygon.io: works although limited to 5 API requests per minute.
