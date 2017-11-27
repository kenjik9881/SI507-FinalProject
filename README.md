# SI507-FinalProject

I am interested in scraping information from coinmarketcap.com to pull in data of the Top 10 cryptocurrencies.
This data will contain the:
• Market Cap
• Price
• Circulating Supply
• Price change over last 24H

I will also pull off historical data about just Bitcoin. This will look at the High price for each day over the last past month. It will pull the date and high price for Bitcoin for this time period.

### Part 1: Scraping the homepage using BeautifulSoup

- [ ] Start with Coinmarketcap's main web page: https://coinmarketcap.com/currencies
- [ ] Use the cached data (if available), if not request information. (Use code from Project 3)
- [ ] Extract data from this page, getting the following information for the Top 10 cryptocurrrencies
    - Market Cap
    - Price
    - Circulating Supply
    - Price change over last 24H
- [ ] Parse this data using BeautifulSoup
- [ ] Create a class called Cryptocurrency that will pass through the information gathered
    - Therefore every crypto for the top 10 crypto's will have those four pieces of information

### Part 2: Scraping the Bitcoin page to get historical price data

- [ ] Use Coinmarketcap Bitcoin page: https://coinmarketcap.com/currencies/bitcoin/historical-data/
- [ ] Use the cached data (if available), if not request information. (Use code from Project 3)
- [ ] Extract data from this page, getting the last month's worth of price information.
    - Date
    - Closing Price
    - Market Cap for that day
- [ ] Parse this data using BeautifulSoup



