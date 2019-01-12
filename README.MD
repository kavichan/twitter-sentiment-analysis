Twitter Sentiment Analysis

The goal of this project is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify biased (racist or sexist tweets) from normal tweets.
Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, our objective is to predict the labels on the test dataset.

Requirements
There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.

numpy,pandas,WordCloud,stopwords,matplotlib,TextBlob,Word
scikit-learn,scipy,nltk,imblearn

The library requirements specific to some methods are:

keras with TensorFlow backend for RNN (LSTM), and CNN.
xgboost for XGBoost.
Note: It is recommended to use Anaconda distribution of Python.

Project file : 
SentimentAnalysis.ipynb : Python code used for this project

Information about other files : 
train_tweets.csv : Contains training data
test_tweets.csv : Contains testing data
glove.twitter.27B.100d.txt:GloVe words vectors from StanfordNLP which match our dataset for seeding word embeddings.