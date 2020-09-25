# NSL-Sentiment-Analysis
Repository for storing files related to the project on analysing tweets regarding the implementation of National Security Law in Hong Kong.

On 30 June 2020, the National Security Law was enacted in Hong Kong, imposing harsh penalties to the communist party’s dissidents and gives the authorities extensive power to target activists who support Hong Kong's independence and pro democracy protests. This project aims to discover people's feelings towards this by analysing the tweets posted regarding the law.

Core questions of this reasearch:
* How does people feel about the Law?
* What actions will they do in response to the Law?

Facing unlabelled data available on Kaggle (HK_df), my first approach was to adopt unsupervised learning. However, considering the incompetance of the data set, I later switched to using SentimentIntensityAnalyzer provided by Vader.
