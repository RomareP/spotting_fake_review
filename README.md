# Spotting Fake Reviews
The reviews today are increasingly held in consideration by users when they have to make a decision. 
The companies that make the content give much importance, for instance, to their online reputation and to digital marketing. 
Basically before making a purchase the reviews of other users are examined to see if the seller is reliable. 
Together with the fake reviews, the problem of the truth of online information expands if we consider identity verification, market protection, brand management, malicious behavior and data journalism.

## In this project the aim is to find a method to detect fake reviews
1. work in the human language and translate it into processable data.

## Dataset
1. Positive Polarity:
- Truthful: 400 reviews;
- Deceptive: 400 reviews.
2. Negative Polarity:
- Truthful: 400 reviews;
- Deceptive: 400 reviews.

## Features Extraction
1. From dataset features:
- hotel name;
- polarity;
- text of the review;
- truthfulness; <br> <br>
We extract: <br>
- Number of words
- Number of characters
- Average word length
- Number of stopwords
- Number of numerics
- Number of uppercase
- Metric avg sentence length
- Metric polarity
- Flesch kincaid grade
- Coleman liau index
- Automated readability index

2. TF-IDF
3. Count Vectorizer

## Models
We investigate many methods from the following categories: <br>
Ensemble Methods, Gaussian Processes, Linear Model, Navies Bayes, Nearest Neighbor, Support Vector Machine, Trees.

## Evaluations
Confusion Matrix, ROC Curve.
