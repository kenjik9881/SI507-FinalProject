# SI507-FinalProject

General Requirements:
- [ ] __repr__ method
- [ ] __contains__ method
- [ ] __repr__ method
- [ ] Two database tables, with at least one relationship between them
- [ ] 15 test methods
- [ ] 2 Unittest classes
- [ ] one setUp and one tearDown

I am interested in scraping information from coinmarketcap.com to pull in data of the Top 10 cryptocurrencies.
This data will contain the:
- [ ] Market Cap
- [ ] Price
- [ ] Circulating Supply
- [ ] Price change over last 24H

I will also pull off historical data about just Bitcoin. This will look at the High price for each day over the last past month. It will pull the date and high price for Bitcoin for this time period.

[Updates!]
- [ ] Potential logic: if current price is lower than average of the past thirty days, then trigger buy. 
(Make it green or red for sell)
- [ ] Market data - can also include which market has it currently the lowest so you can market arbitrage and buy bitcoin at the lowest
- [ ] Delete the tables (2 PM, 3 PM--we will want to to delete the tables and update)

What I want to show
- [ ] All cryptos --get historical data
- [ ] Top 10 will update
- [ ] Show which coins are best to buy now
- [ ] Show which exchange you should be buying on

Things to remember:
- [X] Caching should expiry every 1 hour. (Nytimes code?)

### Part 1: Scraping the homepage using BeautifulSoup

- [X] Start with Coinmarketcap's main web page: https://coinmarketcap.com/currencies
- [X] Use the cached data (if available), if not request information. (Use code from Project 3)
- [X] Extract data from this page, getting the following information for the Top 10 cryptocurrrencies
    - Market Cap
    - Price
    - Circulating Supply
    - Price change over last 24H
- [X] Parse this data using BeautifulSoup
- [X] Create a class called Cryptocurrency that will pass through the information gathered
    - Therefore every crypto for the top 10 crypto's will have those four pieces of information

### Part 2: Scraping the Bitcoin page to get historical price data

- [ ] Use Coinmarketcap Bitcoin page: https://coinmarketcap.com/currencies/bitcoin/historical-data/
- [ ] Use the cached data (if available), if not request information. (Use code from Project 3)
- [ ] Extract data from this page, getting the last month's worth of price information.
    - Date
    - Closing Price
    - Market Cap for that day
- [ ] Parse this data using BeautifulSoup

### Part 3: Creating and using Databases
- [ ] Use data from the Homepage to create one database with the data from the top 10 cryptocurrencies
- [ ] Use data from Bitcoin page to create another database with just data from Bitcoin
- [ ] Query the database to compare the Market Cap of Bitcoin on the each to the market cap of Bitcoin on the home page
- [ ] Find the days on which the market cap was higher in the last month compared to the currrent day

### Part 4: Writing Tests
- [ ] Write 15 Test methods and 2 subclasses (Still TBD)

### Part 5: Visualizing the Data
- [ ] Learn how to use Plotly to create a chart that shows the information from Part I, particularly charting the price of the top 10 cryptocurrencies
- [ ] Use plotly to visualize the historical price data of Bitcoin from Part 2
