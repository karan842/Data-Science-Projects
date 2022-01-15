# Twitter Sentimental Analysis
### Sentiment analysis on 1.6 milion tweets

- Find the dataset here: https://www.kaggle.com/karan842/twitter-sentimental-analysis/data 

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Twitter%20Sentimental%20Analysis/tweet.jpg' height=800px width=800px></img>

Follow me on twitter: https://twitter.com/KuchBhiKaran
 ## 🔵 About Project
 Twitter is one of the most famous social media platform on which we can share our thoughts, opinion and trending related tweets in the form of text, images and videos. In this task I am going to analyze sentiments of tweets which are in the form of tweets.
 I collected this data from **Kaggle**. As the task is depeneded on tweets which texts so this is a problem of **Natural Languages Processing**. There are 1.6 milion tweets in this data so dataset is very huge.
 Main task is to predict sentiments behind tweeet that means, is tweet is positive? or negative? By this strategy we can find good or bad tweets I mean which tweets are harmful and disrespectful according to Twitter guidlines.
 
 ## 🔵 Context:
 The dataset being used is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the Twitter API. The tweets have been annotated (0 = Negative, 4 = Positive) and they can be used to detect sentiment.

[The training data isn't perfectly categorised as it has been created by tagging the text according to the emoji present. So, any model built using this dataset may have lower than expected accuracy, since the dataset isn't perfectly categorised.]

It contains the following 6 fields:

sentiment: the polarity of the tweet (0 = negative, 4 = positive)
ids: The id of the tweet (2087)
date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
flag: The query (lyx). If there is no query, then this value is NO_QUERY.
user: the user that tweeted (robotickilldozr)
text: the text of the tweet (Lyx is cool)
We require only the sentiment and text fields, so we discard the rest.

Furthermore, we're changing the sentiment field so that it has new values to reflect the sentiment. (0 = Negative, 1 = Positive).

## 🔵 Approach:
1. Collected data from Kaggle
2. Imported with essential steps and created a visual that describes number of positive and negative tweets.
3. Text Processing:  steps taken are Lower Casing,
                     - Replacing Emojis,
                     - Replacing Usernames,
                     - Removing Non-Alphabets,
                     - Removing Consecutive letters,
                     - Removing Short Words,
                     - Removing Stopwords,
                     - Lemmatizing.
4. For this project I am using **NLTK** library. You can use spaCy3 or other.
5. By WordCloud I displayed important words from negative and positive tweets.
6. Splitted a data into training and testing data.
7. Created 3 different types of model for better results and accuracy: Bernoulli Naive Baye(Bernoulli)
Linear Support Vector Classification (LinearSVC)
Logistic Regression (LR).
8. Evaluated 3 models by classification report and confusion matrix.
9. Select best model among them.
10. Saved the models
11. Write a function which can predict sentiment of tweets.
12. Took some sentences and found their sentiments.


## 🔵 Thank You!
 
