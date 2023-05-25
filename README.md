# Msc-DSS-Thesis
This repository contains contains the code files that were written for my master thesis in Data Sceince & Society. In this thesis we investigated to what extent sentiment data can help machine learning models to predict stock returns. We include news articles sentiment and twitter sentiment.

1 Collect_EODHD: This file collects news articles from EODHD through their API. 

1 Collect_mediastack: This file collects news articles from Mediastack through their API. 

1 Collect_tweets: This file collectes tweets using snscrape through Twitter's API. 

2 Merge & Format: This file merges and formats the collected data.

3 Sentiment: This file cleans and prepares the data and performs the sentiment analysis. Note that this code was written using the code from https://catriscode.com/2021/05/01/tweets-cleaning-with-python/. 

4 Pre-processing: This file cleans and pre-processes the stock information. It also adds the sentiments from previous file.

5 Trained Models: This file trains the ML models.

6 Strategy: This file processes the results and creates investment strategies.

