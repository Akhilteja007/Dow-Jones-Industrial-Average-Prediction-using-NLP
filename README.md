Dow Jones Industrial Average (DJIA) prediction 
We will be predicting the DJIA closing value by using the top 25 headlines for the day.

The Dow Jones Industrial Average, Dow Jones, or simply the Dow, is a stock market index that measures the stock performance of 30 large companies listed on stock exchanges in the United States.

Content:

There are two channels of datasets used:

News data which is crawled historical news headlines from Reddit WorldNews Channel (Links to an external site.) (/r/worldnews). They are ranked by reddit users' votes, and only the top 25 headlines are considered for a single date.
(Range: 2008-06-08 to 2016-07-01)

Stock data: Dow Jones Industrial Average (DJIA) is used to "prove the concept".
(Range: 2008-08-08 to 2016-07-01)

 three data files in .csv format used:

RedditNews.csv: two columns
The first column is the "date", and the second column is the "news headlines".
All news are ranked from top to bottom based on how hot they are.
Hence, there are 25 lines for each date.

DJIA_table.csv:
Downloaded directly from Yahoo Finance 

CombinedNewsDJIA.csv:
The first column is "Date", the second is "Label", and the following ones are news headlines ranging from "Top1" to "Top25".

Projected ML techniques:

We are going to use different models such as Ridge regression, Xg boost, Random forest to predict DJIA value and then compare the results of each of the models.

Here is the link to data from Kaggle:

https://www.kaggle.com/aaron7sun/stocknews
