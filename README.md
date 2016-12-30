# Jakub neumi anglicky, takze to ma cele spatne!!!!



# Sentiment analysis
Repository for everything we use to win [SOČ](http://www.soc.cz) in 2017.<!--- Our work is focusing on sentiment analysis of public opinion on big world problems, like terrorism and migration. We are using social networks ([Twitter](https://twitter.com)) and well known discussion forums ([Reddit](https://www.reddit.com), [4chan](http://www.4chan.org)).--->
## Technicals
All code is written in [python3.5.2](https://www.python.org/downloads/release/python-352/).
#### Twitter
We are using python library [tweepy](https://github.com/tweepy/tweepy) for accessing Twitter API.
#### Reddit
We are using python library [praw](https://github.com/praw-dev/praw) for accessing Reddit API.
#### 4chan
We are using python library [basc_py4chan](https://github.com/bibanon/BASC-py4chan) for accessing 4chan API.
#### Sentiment analysis
For initial analysis are using out-of-the-box python library [textblob](https://github.com/sloria/TextBlob) for both work with text (tokenizing, word tagging, ...) and sentiment analysis. For deeper analysis we are using [custom sentiment classifier](https://pythonprogramming.net/sentiment-analysis-module-nltk-tutorial/) written in python with library [nltk](http://www.nltk.org). We have two classifiers, each has same architecture, but is trained on different dataset. One is trained on labeled [movie reviews](https://pythonprogramming.net/new-data-set-training-nltk-tutorial/). Second is trained on labeled [tweets dataset](https://inclass.kaggle.com/c/si650winter11/data). The second one is preferable for our purpose.
