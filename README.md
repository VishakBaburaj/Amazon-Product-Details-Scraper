# Amazon Product Details Scraper
## Libraries
1) from selenium import webdriver
2) import pandas as pd
3) from tqdm import tqdm

## Steps to scrape product names, prices, links, ratings and reviews
1) Connected to the chromedriver.
2) URL for scraping.
3) Empty dictionary for product names.
4) Empty dictionary for prices.
5) Using dictionary because some items do not have prices. we can eliminate these items by utilizing keys which are available for dictionaries and not lists.
6) xpath for all the product names.
7) xpath for all the prices.
8) For loop to get all the product names.
9) href for creating a link between product and price.
10) For loop to get all the prices.
11) Selecting only the final price and ignores the currency symbol, discount, etc.
12) The href link ensures that a product's name and price are taken only if both of them exist.
13) Empty list to store everything scraped.
14) Adding the scraped data to the list.
15) Storing the data in a dataframe and also renaming the columns.
16) Exporting the dataframe to csv
17) Function to scrape the reviews.
18) Function to scrape the ratings.
19) Creating new columns and appending the ratings and reviews.
20) Exporting the data scraped into an excel file.



