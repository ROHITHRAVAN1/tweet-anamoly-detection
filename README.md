# tweet-anamoly-detection
# Anomaly/Outlier detection is one of very popular topic in ML world. It
comes under ‘unsupervised learning’ process. Here we don’t have any
prior knowledge of the data patterns unlike ‘supervised learning’.
‘Anomaly or Outlier’ is that data point which is not that much similar
with other data points in our entire data set.
Now a days, we are spending the most of the time online in the social
media. The example for such social media is Twitter, Facebook and
Instagram. Here in our project we are gone help the users to identify the
how far a tweet is true or else it was an anomaly.
I will use Python, Sci-kit learn, ‘pyod’ library from ‘pypi.org’, Gensim,
NLTK for solution of this problem.
• Data is from Kaggle Donald_Tweets we use
https://www.kaggle.com/austinreese/trump-tweets
• After getting the data we now have to select the data on which we
are going to work
• After that we convert the text to vector by doc2vec function
• After that we use PCA to identify principal components
• After that we cluster the data
• After that we find the Silhoutte Score
• After that we sort the scores
• Find the least scores that are nearer to zero
• Then we go for anomaly detection by basing on the Silhoutte
Score if Silhoutte Score= 0
• Finally we will be able to view anomaly tweets.
