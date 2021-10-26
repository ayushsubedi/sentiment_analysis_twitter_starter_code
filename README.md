# Twitter Sentiment Analysis

### Getting data from twitter
1. Using Tweepy (uses official twitter API)
- easy
- several limitations
- check https://developer.twitter.com/en/docs/rate-limits

2. Using Twint (unofficial)
- a little difficult
- less limitation
- amazing for large volume


_______________________________


### Analysis
- Vader sentiment using python package https://towardsdatascience.com/sentimental-analysis-using-vader-a3415fef7664
- Naive bayes for sentiment analysis (a little of DIY) https://www.datacamp.com/community/tutorials/simplifying-sentiment-analysis-python
- Spacy package
- Gensim package
- etc.

_________________________________


# Installation 

#### Clone the repo

`git clone https://github.com/cloudfactory/sentiment_analysis_twitter_starter_code`


#### CD into the cloned directory and create a virtualenv

`python -m venv env`

### Enable virtualenv

`source env/bin/activate`

### Install dependency packages from requirements.txt

`pip install -r requirements.txt`

### Oper jupyter lab session

`jupyter-lab`
