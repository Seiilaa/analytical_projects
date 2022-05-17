# Popularity of "Ukraine" search word in Google Trends

## Project tasks

* Got data from Google Trends on the specified search word using pytrends package.
* Did popularity of the word analysis by region and time. Decomposed the data to reveal weekly seasonality to the search popularity.
* Visualized the findings.

## Code and resources used

**Python Version:** 3.10.2

**Packages:** pandas, statsmodels, pytrends, matplotlib, seaborn

**Resources:** [The Ultimate Guide To PyTrends](https://lazarinastoy.com/the-ultimate-guide-to-pytrends-google-trends-api-with-python/#interestbyregion), [Google Search Analysis with Python](https://thecleverprogrammer.com/2021/04/27/google-search-analysis-with-python/)

## What do Google Trends values actually denote? 

According to Google Trends, the values are calculated on a scale from 0 to 100, where 100 is the most popularity as a fraction of total searches. Thus it is important to remember that the values don't depict an absolute number of searches. 
"A higher value means a higher proportion of all queries, not a higher absolute query count. So a tiny country where 80% of the queries are for "bananas" will get twice the score of a giant country where only 40% of the queries are for "bananas"."
