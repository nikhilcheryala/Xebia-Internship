# Sentiment Analysis Project
## Overview
This project involves performing sentiment analysis on a dataset of tweets. The goal is to classify tweets as either positive or negative. The project includes data preprocessing, exploratory data analysis (EDA), model building using LSTM, and visualization of results using Power BI.

## Table of Contents
Overview
Dataset
Preprocessing
Exploratory Data Analysis (EDA)
Model Building
Evaluation
Power BI Dashboard

## Dataset
The dataset used for this project contains tweets labeled as positive (1) or negative (0). It includes the following columns:

label: Sentiment of the tweet (0 for negative, 1 for positive)
time: Time of the tweet
date: Date of the tweet
query: Query used (if any)
username: Username of the tweet author
text: The tweet content
## Preprocessing
###Steps:
Lowercasing text
Removing stop words
Removing punctuations
Removing repeating characters
Removing email addresses
Removing URLs
Removing numeric characters
Tokenization
Stemming
Lemmatization
## Exploratory Data Analysis (EDA)
###Key Insights:
Label Distribution: Proportion of positive vs. negative tweets.
Tweet Length Distribution: Distribution of the lengths of tweets.
Most Common Words: Word clouds for positive and negative tweets.
Top Influencers: Users with the most positive and negative tweets.
Common Hashtags: Frequent hashtags in positive and negative tweets.
## Model Building
An LSTM model is built using TensorFlow and Keras to classify the sentiment of the tweets.

## Model Architecture:
Input Layer: Tokenized tweet text
Embedding Layer: Converts text to vectors
LSTM Layer: Captures sequential dependencies
Dense Layer: Fully connected layer with ReLU activation
Dropout Layer: Prevents overfitting
Output Layer: Sigmoid activation for binary classification
## Evaluation
###Metrics:
Accuracy: Overall accuracy of the model on the test set.
Confusion Matrix: True positives, true negatives, false positives, and false negatives.
ROC Curve: Performance of the classification model at different thresholds.
## Power BI Dashboard
###Visualizations:
Total Users 
Top user with more time
Top user with More tweets
Total Tweets: Total number of tweets analyzed.
Positive Tweets: Number of positive tweets.
Negative Tweets: Number of negative tweets.
Label Distribution: Pie chart showing positive vs. negative tweets.
