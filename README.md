# Amazon Review Sentiment Analysis

This project performs sentiment analysis on the Amazon Fine Food Reviews dataset using two different models: VADER (a lexicon-based approach) and a pre-trained RoBERTa model (a transformer-based approach). The goal is to compare their performance in classifying reviews as positive, neutral, or negative.

## Dataset

The dataset used in this project can be found on Kaggle:
[Amazon Fine Food Reviews Dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

## Results

The confusion matrices below compare the predicted sentiment to the actual sentiment (derived from the star ratings).

### VADER Confusion Matrix

![VADER Confusion Matrix](vader_matrix.png)

### RoBERTa Confusion Matrix

![RoBERTa Confusion Matrix](roberta_matrix.png)
