## Project: Twitter Sentiment Analysis

### Install
This project requires **Python 2.7** or above and the following Python libraries installed:

numpy
pandas
WordCloud
stopwords
matplotlib
TextBlob
Word
scikit-learn
scipy
nltk
imblearn

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

### Code
SentimentAnalysis.ipynb : Python code used for this project

### Run

In a terminal or command window, navigate to the top-level project directory `sentimentanalysis/` (that contains this README) and run one of the following commands:

```bash
ipython notebook SentimentAnalysis.ipynb
```  
or
```bash
jupyter notebook SentimentAnalysis.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

The goal of this project is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify biased (racist or sexist tweets) from normal tweets.
Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, our objective is to predict the labels on the test dataset.


Information about other files : 
train_tweets.csv : Contains training data
test_tweets.csv : Contains testing data
glove.twitter.27B.100d.txt:GloVe words vectors from StanfordNLP which match our dataset for seeding word embeddings.