# NSL-Sentiment-Analysis
Repository for storing files related to the project on analysing tweets regarding the implementation of National Security Law in Hong Kong.

On 30 June 2020, the National Security Law was enacted in Hong Kong, imposing harsh penalties to the communist party’s dissidents and gives the authorities extensive power to target activists who support Hong Kong's independence and pro democracy protests. This project aims to discover people's feelings towards this by analysing the tweets posted regarding the law.

Core questions of this reasearch:
* How does people feel about the Law?
* What actions will they do in response to the Law?

Log:
24/9: Facing unlabelled data available on Kaggle (HK_df), my first approach was to adopt unsupervised learning. However, due to the lack of online resource on supervised sentiment analysis, I turned to SentimentIntensityAnalyzer provided by Vader.
25/9: Although SentimentIntensityAnalyzer could provide sentiment scores, plotting the results on a graph is meaningless because the original data set has only date but no time. Also the tweets concentrate on a few dates only, making it impossible for me to draw conclusions. Now I consider applying for tweeter developer account for the use of tweepy.
