# **📰 News Classifier using TF-IDF and XGBoost**

This project implements a news classifier that automatically categorizes news text into fraud and real using TF-IDF (Term Frequency–Inverse Document Frequency) for feature extraction and XGBoost for classification.

## 🚀 Project Overview

The goal of this project is to build a robust machine learning model capable of classifying news articles fraud or real based on their textual content.

We use:

TF-IDF to convert raw text into numerical features.

XGBoost, a powerful gradient boosting algorithm, is used to perform the classification.



## 🧠 Key Features

Preprocessing of raw text (tokenization, stopword removal, etc.)

Vectorization using TF-IDF

Training and tuning an XGBoost classifier

Evaluation using precision, recall, F1-score, and confusion matrix

Support for new, unseen news article predictions


## 🧹 Data Preprocessing

The preprocessing pipeline includes:

Lowercasing

Removing punctuation, numbers, and stopwords

Lemmatization (optional)

TF-IDF vectorization for feature extraction

Example:
