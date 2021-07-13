# Twitter sentiment analysis - COVID19

This notebook process basic sentiment analysis that is one of the
tools of NLP (Natural Language Processing). 

The goal is to analyse current global topic **COVID-19** by extracting number of tweets from Twitter containing keyword "covid19". 

To get data I am going to use **Tweepy** library to access Twitter API, which is available to anyone after creating a Twitter developer account.

Extracted data is going to be cleaned and prepared for following sentiment analysis by using **TextBlob** library.

Finally I am going to visualize the data as **WordClouds**, which is an easy way to find and display the most common words in provided text.
