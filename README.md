# SEC Financial Data
The SEC maintains a database (EDGAR) of financial data reported from all walks of industry that describes a complete account of the company's performance. In this project, I demonstrate how to navigate the SEC database to find 10-k filings, which are the recepticle for the specific reports themselves. I write functions that make use of SEC nomenclature to automatically the navigate various database hierarchies and finally arrive at desired 10-k's. Then, I make use of scraping to pull financial data from the documents held within the 10k, store it in a dataframe, and plot my findings.

The process requires supervision, as the sec hierarchy is not completely ubiquitous. This process could be even more automated with a some alterations, and be used to pull and scrape data from financial documents of many companies.

Next, I look at stock price data and use a random-forests classifier to predict whether the stock will move up or down on the next day. The model is able to predict with very reasonable accuracy the direction of the stock price movement
