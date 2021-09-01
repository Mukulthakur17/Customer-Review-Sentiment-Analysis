# Customer Review Sentiment Analysis

## Problem Statement

- Given a text and a *"*phrase*"* from it, detect the sentiment expressed towards the *"phrase"* in the text instance.

**Examples**

- cannot rely on both milk delivery and grocery | milk | Negative
- your customer service is terrible! | customer service | Negative
- i love notion as a tool | tool | Positive
- notion is a great site and an Iphone app. | notion | Positive
- Asked for a workspace name or billing email address | billing | Neutral

**Motivation**

- Model evaluation is based on performance on only Positive and Negative classes since samples with neutral class lead to no insight for our users.

## We have trained 3 different models:
- Using BERT Model
- USing RNN Classifier
- Using ML Algorithms

## Content
`notebooks`: Contains the code for all 3 classifiers.\

`data`: Contains the train and test data.\

`models`: Contains the trained model.

