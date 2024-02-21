# Twitter Sentiment Analysis

Notebook with my code on the Kaggle competition: [Tweet Sentiment Extraction](https://www.kaggle.com/competitions/tweet-sentiment-extraction)

Data: train.csv and test.csv

_Copied from Kaggle:_

With all of the tweets circulating every second it is hard to tell whether the sentiment behind a specific tweet will impact a company, or a person's, brand for being viral (positive), or devastate profit because it strikes a negative tone. Capturing sentiment in language is important in these times where decisions and reactions are created and updated in seconds. But, which words actually lead to the sentiment description? In this competition you will need to pick out the part of the tweet (word or phrase) that reflects the sentiment.

Help build your skills in this important area with this broad dataset of tweets. Work on your technique to grab a top spot in this competition. What words in tweets support a positive, negative, or neutral sentiment? How can you help make that determination using machine learning tools?

In this competition we've extracted support phrases from Figure Eight's Data for Everyone platform. The dataset is titled Sentiment Analysis: Emotion in Text tweets with existing sentiment labels, used here under creative commons attribution 4.0. international licence. Your objective in this competition is to construct a model that can do the same - look at the labeled sentiment for a given tweet and figure out what word or phrase best supports it.

Disclaimer: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.

# Method

My code is based on the pre-trained huggingface model [distilbert-based-uncased](https://huggingface.co/distilbert/distilbert-base-uncased) and provides an accuracy of 89% on the evaluation data.

# Model

The trained model and inference API can be found [here](https://huggingface.co/suryaR-15/twitter-sentiment-extraction-distilbert).
