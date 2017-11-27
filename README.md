# SI507-FinalProject

I am interested in scraping information from coinmarketcap.com to pull in data of the Top 10 cryptocurrencies.
This data will contain the:
• Market Cap
• Price
• Circulating Supply
• Price change over last 24H

I will also pull off historical data about just Bitcoin. This will look at the High price for each day over the last past month. It will pull the date and high price for Bitcoin for this time period.

### Part 1: Scraping using BeautifulSoup

- [ ] Start with Coinmarketcap's main web page: https://coinmarketcap.com/currencies
- [ ] Extract data from this page, getting the following information for the Top 10 cryptocurrrencies
    - Market Cap
    - Price
    - Circulating Supply
    - Price change over last 24H
- [ ] Parse this data using BeautifulSoup
- [ ] Create a class called Cryptocurrency that will pass through the information gathered
    - Therefore every crypto for the top 10 crypto's will have those four pieces of information
- For each Front Page article
    - [ ] Get (and cache) that article's web page
    - [ ] Extract its related coverage of articles, and
    - [ ] Save its title, thumbnail, date, and link (What data structure will you use? Where will you save it?)
