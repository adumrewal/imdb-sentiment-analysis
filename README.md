# IMDb_sentiment_analysis
IMDB movie review sentiment classification is a popular problem. The data contains 25k highly-polar (good or bad) movie reviews for training and testing. The objective is to predict whether a given movie review has a positive or negative sentiment.

### Following is the description for IMDb_seq2seq
The codes are generated using *keras* with Tensorflow backend.
The above code generates a *sequence-to-sequence autoencoder* from the vectorized review of maximum length 'max_review_length' containing only the top 'top_words' most frequent words. The embedding generated is then used to classify the review as good or bas using a simple Deep Learning model.
The code hasn't been optimized but can be used to develop better classifier and can be used as a basic structure for using sequence-to-sequence autoencoder in keras.
