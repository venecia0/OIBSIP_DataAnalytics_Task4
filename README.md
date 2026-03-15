# OIBSIP_DataAnalytics_Task4
Sentiment Analysis
# Sentiment Analysis on Twitter Data

## Project Overview

This project performs sentiment analysis on Twitter text data using Natural Language Processing (NLP) and machine learning techniques. The aim is to identify the sentiment expressed in tweets and categorize them as positive, negative, or neutral. This type of analysis helps in understanding public opinion and trends from social media data.

## Dataset

The dataset contains Twitter messages that are already labeled with sentiment categories:

* **1** → Positive
* **0** → Neutral
* **-1** → Negative

These labels help train a machine learning model to recognize the sentiment expressed in different tweets.

## Objective

The primary objective of this project is to analyze textual data from Twitter and build a model capable of automatically predicting the sentiment of tweets.

## Project Steps

The following steps were performed during the analysis:

1. Loaded and explored the dataset
2. Cleaned the text data by removing unnecessary characters and symbols
3. Performed text preprocessing such as stopword removal and normalization
4. Converted text data into numerical features using **TF-IDF Vectorization**
5. Trained a machine learning model for sentiment classification
6. Evaluated model performance using different evaluation metrics
7. Visualized sentiment distribution and classification results

## Machine Learning Model

* **Algorithm Used:** Multinomial Naive Bayes
* **Feature Extraction Method:** TF-IDF Vectorization

## Tools & Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Outcome

The trained model successfully categorized tweets into positive, neutral, and negative sentiments. The performance of the model was evaluated using metrics such as accuracy score, classification report, and confusion matrix.

## Conclusion

This project demonstrates how Natural Language Processing and machine learning techniques can be applied to analyze social media data. It provides insights into how textual data can be processed, transformed into features, and used to train predictive models for sentiment classification.

