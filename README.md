# NSL-Sentiment-Analysis
Repository for storing files related to the project on analysing tweets regarding the implementation of National Security Law in Hong Kong.

On 30 June 2020, the National Security Law was enacted in Hong Kong, imposing harsh penalties to the communist party’s dissidents and gives the authorities extensive power to target activists who support Hong Kong's independence and pro democracy protests. This project aims to discover people's feelings towards this by analysing the tweets posted regarding the law.

Core question: How does people feel about the Law?

## Methodology
Facing unlabelled data, I chose to adopt SentimentIntensityAnalyzer from Vader. Then, I analysed the change of sentiment and the overall sentiment by plotting, assuming the classification result is correct.

## Conclusion
Concluding the project, I do not think that I have met my expectation:
* The source data is from Twitter only. Since the majority of HKers use other social platforms, this result could be biased.
* Vader may not have done a good job in classifying people's sentiment. While people are angry/sad, they may post things that encourage each other, or call for some collective action. This may create false analysis saying that people are generally positive "about the Law".
* The classification in the end is linear.

I will try to do better in the following aspects:
* Find ways to work better with unlabelled data using unsupervised learning.
* Get my own dataset using Twitter's developer API.

## Blibiography
* This Is How Twitter Sees The World : Sentiment Analysis (Ronald Wahome)
* Sentiment Analysis of Anthem’s Game Launch in Python (William Masse)
