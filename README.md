# Project 1 : Bitcoin As A Viable Investment
![invest_stock](https://user-images.githubusercontent.com/117343047/218954549-b9403d70-0580-43fb-ad9c-1ead2f932b18.jpg)
## Background
Capital Investments, LLC is looking to stay ahead of the market trends and stay competitive in hopes of bringing in new clientele. One of the trends that is being evaluated is cryptocurrency, Bitcoin in particular. The objective of this project is to analyze and to determine the following: 
Is Bitcoin a viable short or long term investment? 
Does Bitcoin have a correlation with SPHQ, OIL, or GOLD?
What is the best investment option for a long term portfolio?

## Technologies Used
* API (https://www.alphavantage.co/)
* CSV files 
* Matplotlib 
* Python 
* Jupyter notebook
* Pandas 
* Git Hub

## Data source
* Kaggle (https://www.kaggle.com/datasets/sourabhkumarburnwal/bitcoin-and-stock-market-datasets)
* API (https://www.alphavantage.co/)

## Description of Data Exploration
This project used information gathered from an API, Alphaventage. The data for S&P500, Gold, Oil, and Bitcoin were collected. A dataset from Kaggle was also used to complete the data set from 2013 to 2020 for Bitcoin. For S&P500, Gold, and Oil had indexes that were used to represent each object, explaining why they stay at the range 10 to 50 dollars. As for Bitcoin, it used the amount of 1 cryptocurrency’s value. The datasets had no missing values, for SPHQ, Gold, and Oil every 7 days the database is missing two, that is because there is no data for the indexes on the weekend’s. 
It was collected from the API the information: date, open (price), low (price), high (price), and close (price), the columns names are the same without ‘(price)’. And two new columns were added, one for the symbol of the index and another for calculation the percentage daily price change ( [close - open] / open )

## Data Analysis


## Limitations of the Dataset and Future Consideration
Since, we only examined three other stocks to determine if Bitcoin was correlated. The dataset was too small to determine if there is a stock that does have a correlation. If we had additional time for this project we could have explored additional ETFs, stocks, etc. to have a large data sample to test. BTC being an emerging investment in 2009 had unusually large profits and inconsistancies in the data. The GOLD data set was for a gold mining company. If we had analyize the data for the resources itself, the analysis results may have varied. Similar to GOLD, SPHQ is an index of the top 100 performing companies of the SP500. It would have been interesting to see if we had collected more sub indexes of sp 500 and determine the overall correclation between Bitcoin and SP500. Expanding the research on cryptocurrency, the team could also analyized the information for alternative cryptocurrencies.  




## Contributors
* Jacob Darmofal
* Vincent Elequin
* Sean Smith
* Alexandre Maule
