# Generate-New-Tweets-Based-on-Existing-Tweets.
Machine Learning model to generate new tweets based on the user's existing tweets
Dataset : https://www.kaggle.com/kazanova/sentiment140
Cleaning : Removed stop-words, punctuations, urls and more useless things then used Lemmatizer to get features
Feature Extraction : used count_vectorizer to get top features and trained model on those features
Used MultinomialNB to classify Whether tweets neg or positive, got a accuracy of 79%, then for generation of new tweet first predict category of tweet from our model then from that category in our training data return a tweet.
