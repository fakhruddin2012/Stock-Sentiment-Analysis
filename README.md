# Stock-Sentiment-Analysis
Stock Sentiment Analysis using News Headlines 
## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Approach](#Approach)

## Problem Statement:
In this project, I am trying to predict whether the stock price will increase or decrease with the help of news headlines.

## Approach:
The dataset contains news headlines of sixteen years from 2000 to 2016. If the stock price increases it is labelled as 1 or if decreases it is labelled as 0.

The dataset required pre text cleaning which i did with the help of regular expressions.

I considered data upto 2014 as training data and from 2015 I took the data for testing.

After cleaning the dataset I used CountVectorizer to vectorize the text.

I used Random Forest classifier for prediction.

I got the accuracy score of 84.65%.
