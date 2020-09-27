# NSL-Sentiment-Analysis
Repository for storing files related to the project on analysing tweets regarding the implementation of National Security Law in Hong Kong.

On 30 June 2020, the National Security Law was enacted in Hong Kong, imposing harsh penalties to the communist party’s dissidents and gives the authorities extensive power to target activists who support Hong Kong's independence and pro democracy protests. This project aims to discover people's feelings towards this by analysing the tweets posted regarding the law.

## Core questions
* How does people feel about the Law?
* What actions will they do in response to the Law?

## Log
24/9: Facing unlabelled data available on Kaggle (HK_df), my first approach was to adopt unsupervised learning. However, due to the lack of online resource on supervised sentiment analysis, I turned to SentimentIntensityAnalyzer provided by Vader.

25/9: Although SentimentIntensityAnalyzer could provide sentiment scores, plotting the results on a graph is cannot give much insights because the original data set has only date but no time; the tweets also concentrate on a few dates only. Now I consider applying for tweeter developer account for the use of tweepy.

27/9: Since my Twitter developer account got approved, I started developing another solution using the Twitter RESTful API.

## Blibiography
* This Is How Twitter Sees The World : Sentiment Analysis Part One (Ronald Wahome)
* Sentiment Analysis of Anthem’s Game Launch in Python (William Masse)
