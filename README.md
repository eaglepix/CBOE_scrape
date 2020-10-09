# CBOE_scrape
Scraping options data from CBOE website and making simple analysis and charts such as Put-Call ratio.

#### Note: This is valid as at Oct 9, 2020, future changes in CBOE website may render this program inoperable

- The CBOE options market statistics website has organized table format without protection, hence it is simple to scrape the tables using Pandas.
- Normally, I would convert them to Pandas dataframes, but in this case - since there are multiple tables, I thought the best way is to keep them all in dictionary format and save under one pickle (.pkl) file. Else I would have multiple tables that needed to be stored under separate .csv files.
