# WeRateDogs Twitter Data Analysis
#### by Vedavyas Kamath  <br><br>


## Description:
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The account was started in 2015 by college student Matt Nelson, and has received international media attention both for its popularity.
The goal of the project was to firstly gather related data from various sources, then assess and finally clean up the data in order to make it ready for analysis and find some interesting insights.


## Files used:
Used the files `twitter-archive-enhanced.csv`, `image-predictions.tsv` and `tweet_json.csv` <br>

The data for WeRateDogs was gathered and collected from 3 different sources as listed below:
1. Manually downloaded WeRateDogs enhanced archive from Udacity server.
2. Programmatically downloaded image predictions file using Python & its libraries.
3. Downloaded the data for tweets present in the archive from Twitter by querying the Twitter API and  using the Tweepy library in Python.

These files are available for download
[here](https://drive.google.com/file/d/1OuWvOKwL2gYW1MMwTs5fIV352_fOkK3Y/view?usp=sharing)

## Dataset:
The dataset initially contained data from 3 separate files listed above that was messy and along with several quality issues. Identified and addressed 10 quality issues and 2 tidiness issues through the course of this project. <br>
All the quality & tidiness issues are documented clearly in the `wrangle_report.pdf` and a copy of the cleaned dataset is available for download [here](https://drive.google.com/file/d/1G7DTyQu0BQsrE-cUxG_dKkDf-pPhEvC0/view?usp=sharing)


## Summary of Findings & Key Insights:

1. Observed a strong positive co-relation between count of tweets marked as favorites and tweets that were re-tweeted.

2. Golden Retriever happened to be the most popular breed among the list of breeds that were identified.

3. Majority of the tweets about WeRateDogs were posted by users using the iPhone App for twitter.
