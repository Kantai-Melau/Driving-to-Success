# Driving-to-Success
We are trying to set up a start-up car company. We are looking to buy used cars to either sell or give out for hire to clients. For this, it would be beneficial to analyse the existing car market and figure out what type of car (brand,type,year, etc.) is the most financially sound to be invested in. For this we can web-scrape the data from a motor-selling website and analyse a Kaggle dataset of web-scraped cars. We will extract, transform, and load it into PostgreSQL database, this will result in both JSON and CSV files to be processed. 


# Using a CSV

We obtained a csv 'vehicles' from kaggle to be used as a dataset.
- Using python we were able to transform it using the following steps:
a) Imported it into pandas and displayed the data that it contains.
b) Cut out the columns that were unnecesary and not required.
c) Dropped columns that did not have any values.
d) Renamed the columns.

From that the dataframe was ready to be stored in a database
