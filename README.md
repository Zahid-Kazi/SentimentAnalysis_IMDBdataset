# SentimentAnalysis_IMDBdataset
# Overview
This project performs sentiment analysis on the IMDB dataset using various vectorization techniques and Naive Bayes models. The goal is to determine which combination of techniques provides the best accuracy for classifying movie reviews as positive or negative.

# Dataset
The dataset used in this project is the IMDB dataset, which contains 40,000 movie reviews labeled as positive or negative.

# Vectorization Techniques used
CountVectorizer(binary=True)

CountVectorizer(binary=False)

TfidfVectorizer

# Naive Bayes Models used

BernoulliNB

MultinomialNB

# Preprocessing done
Stopword removal

Punctuation removal

# Best Performing Model
The MultinomialNB model using TfidfVectorizer provided the best accuracy after removing stopwords and punctuation.
