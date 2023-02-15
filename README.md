# Project 1 : Bitcoin As A Viable Investment
	
## Background
Capital Investments, LLC is looking to stay ahead of the market trends and stay competitive in hopes of bringing in new clientele. One of the trends that is being evaluated is cryptocurrency, Bitcoin in particular. The objective of this project is to analyze and to determine the following: 
Is Bitcoin a viable short or long term investment? 
Does Bitcoin have a correlation with SPHQ, OIL, or GOLD?
What is the best investment option for a long term portfolio?

## Technologies/Resources Used
* Api (https://www.alphavantage.co/)
* CSV files 
* Kaggle (https://www.kaggle.com/datasets/sourabhkumarburnwal/bitcoin-and-stock-market-datasets)
* Matlablib 
* Python 
* Jupyter notebook
* Pandas 
* Git

## Description of data exploration
This project used information gathered from an API, Alphaventage. The data for S&P500, Gold, Oil, and Bitcoin were collected. For S&P500, Gold, and Oil had indexes that were used to represent each object, explaining why they stay at the range 10 to 50 dollars. As for Bitcoin, it used the amount of 1 cryptocurrency’s value. The datasets had no missing values, for SPHQ, Gold, and Oil every 7 days the database is missing two, that is because there is no data for the indexes on the weekend’s. 
It was collected from the API the information: date, open (price), low (price), high (price), and close (price), the columns names are the same without ‘(price)’. And two new columns were added, one for the symbol of the index and another for calculation the percentage daily price change ( [close - open] / open )

## Data Analysis

## Limitations of the dataset and future consideration
	Exploring additional ETFs, stocks, etc.
	BTC being an emerging investment (2009) 
	Examining additional indices for GOLD and S&P500
	Collecting data on various cryptocurrencies. This will allow for diversification and the introduction of various factors. (price of gas on cryptocurrency)
	Predict futures 

## Contributors
	Jacob Darmofal
	Vincent Elequin
	Sean Smith
	Alexandre Maule
## Data source
