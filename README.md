# Twitter-Troll-Prediction-analysis

## Data set Description:
The data directory contains data on nearly 3 million tweets sent from Twitter handles connected to the Internet Research Agency, a Russian "troll factory" and a defendant in an indictment filed by the Justice Department in February 2018, as part of special counsel Robert Mueller's Russia investigation. The tweets in this database were sent between February 2012 and May 2018, with the vast majority posted from 2015 through 2017.

You can learn more about the data here : https://github.com/fivethirtyeight/russian-troll-tweets

Goal - Twitter troll Prediction using the account categories and other features available in the huge dataset.

Libraries used: Sci-kit learn, NumPy, Pandas, nltk, wordcloud

## Tasks:

Use a smaller sample dataset – we are providing a sample which is 1% of the entire dataset - IRAhandle_tweets_sample_data.csv. This will likely be very useful for prototyping models to figure out what might work well. For example, you might find some algorithms are too slow even on the sample dataset, in which case they will certainly never work on the full dataset.
• The sample data is pre-processed, you would need to carry out the below pre-processing tasks for your master data.

• Make a new column – troll, this column will classify whether the account category of a tweet is troll or not.
➢ For all those rows where account_category = RightTroll or LeftTroll, troll = 1 else 0.

• On the smaller dataset performed ML tasks to see which ones work best and chose them to run on the bigger/main dataset.

# Methods used (on the bigger dataset after data cleaning):  
• Using a Count Vectorizer

• Using TF/IDF

• Using a different classifier

