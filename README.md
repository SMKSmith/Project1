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
The methods the team used to analyize the data was merging the data frames SPHQ, OIL, and GOLD to BTC(Bitcoin) individually. Once the datasets were merge they were put on a graph. We utilized the regression line and the r value to determine the strength of the correlation between the two datasets. The comparison between OIL to BTC was .001 making the correlation non-existant, showing they are independent of each other. The comparison between GOLD and BTC was .39 making is a very weak positive correlation. Since, the value was lower than .45 this shows there is no correlation between GOLD and BTC. Then the comparsion between SPHQ and BTC show a very strong positive correlation at .88. However, analyizing the historical data on a chart show that the two only have similar behaviors in the market from 2021 until now. When the market is unstable, like it is now, BTC correlates to the SP500. When the market stablizes than BTC will go back to normally being independent. 

The analysis if Bitcoin is a viable long or short term investment started by calculating the average daily profit, which came to .11%. The daily profit show little value until the data from 2018 to 2023 show a 69% increase in profits. Reviewing the calculated dataframe below, it can bedetermined that the performance in BTC is no where near previous years. Short term trading of BTC will likely lose profit unless the sell off is within the perfect time before the crash. BTC is high risk and is recommended to be a long term investment over a short term. 
![btc_6 mo](https://user-images.githubusercontent.com/117343047/219000258-3b57d91b-233d-45ef-9772-9c7dc388a8d7.jpg)

The best performing stock from the group is SPHQ and would make for the ideal addition to a long term portfolio. Initially, analyzing the historical stock performance of SPHQ shows the continual upwards growth making it a safe long term investment. The stocks are reviewed twice a year with only the best performing companies remain in the stock index making it well balanced.   

![sp500](https://user-images.githubusercontent.com/117343047/219002426-6d8f50e5-b540-438d-b372-8e79bfa160c1.jpg)

The data below shows a profit snapshot for a 5 year investment. Whether, the stocks were purchased in 2005 or 2015 the index show high yield investments with reliable return rates. 

![SPHQ](https://user-images.githubusercontent.com/117343047/219004330-7951461b-79fc-47d0-b8ce-417b261dd8f1.jpg)

## Limitations of the Dataset and Future Consideration
Since, we only examined three other stocks to determine if Bitcoin was correlated. The dataset was too small to determine if there is a stock that does have a correlation. If we had additional time for this project we could have explored additional ETFs, stocks, etc. to have a large data sample to test. BTC being an emerging investment in 2009 had unusually large profits and inconsistancies in the data. The GOLD data set was for a gold mining company. If we had analyize the data for the resources itself, the analysis results may have varied. Similar to GOLD, SPHQ is an index of the top 100 performing companies of the SP500. It would have been interesting to see if we had collected more sub indexes of sp 500 and determine the overall correclation between Bitcoin and SP500. Expanding the research on cryptocurrency, the team could also analyized the information for alternative cryptocurrencies.  




## Contributors
* Jacob Darmofal
* Vincent Elequin
* Sean Smith
* Alexandre Maule
