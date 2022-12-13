# Twitter Purchase Sentiment Analysis

## Project Overview

In this project I worked with the Twitter Developer API to obtain tweets related to Elon Musk's purchase of Twitter on October 27, 2022. The data obtained was cleaned from Retweets, hashtags and punctuation so that it could be analyzed. After that, a sentiment analysis was carried out to find insights about people's reaction to Twitter's purchase. 

### What you will find

1. Data extraction using Twitter API 2.0 and Tweepy for Python.
2. Sentiment Analysis using NLTK.
3. Data visualization with WordCloud and other graphs.

### Main insights

Through working with Twitter's Developer API 2.0, **5000 tweets related to Elon Musk's Twitter purchase** were requested. This tweets were constrained to be written in english, and were obtained with their public statistics as *number of likes and number of times that they have been retweeted*. Some example of tweets can be seen below: 

![](https://github.com/msbernal/twitter_purchase_analysis/blob/main/assets/result2.png)

After that, it was performed data cleansing of hashtags, RT and other punctuation, to proceed with a Sentiment Analysis using NLTK's Sentiment Analyzer. **Out of the 5000 tweets obtained, 2313 were identified as Positive Sentiment tweets (46.26%), 984 (19.68%) as Neutral Sentiment tweets, and 1703 (34.06%) as Negative Sentiment tweets**. Then the acumulated number of likes and retweets were obtained, as a form of see the impact of the positive, neutral and negative tweets in other users. 

![](https://github.com/msbernal/twitter_purchase_analysis/blob/main/assets/result1.png)

After that it was performed data visualization of the main words used in the tweets with WordCloud. Differences between the positive and negative sentiment tweets were seen, such as:
1. The much greater use of words as "Trump", "hate", "banned" in negative-sentimented tweets. 
2. The greater use of "free spech", "will", "good" and "better" in positive-sentimented tweets.

![](https://github.com/msbernal/twitter_purchase_analysis/blob/main/assets/result4.png)
![](https://github.com/msbernal/twitter_purchase_analysis/blob/main/assets/result3.png)


### Improvements to do: 

Despite the insights made above, it was also noted that some tweets were not strictly related to Elon Musk's purchase of Twitter. Some of then, for example, were related to the actions Musk would take after the purchase, or the anouncement of advertiser's leaving the platform. Further analysis in the Twitter API Query could be done with a Twitter API Researcher's account.


### Python Dependencies:
* [Tweepy](https://www.tweepy.org/)
* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [Matplotlib](http://matplotlib.org/)