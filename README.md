# Tweets_sentiment_analysis_

📌 Overview

This project performs sentiment analysis on tweet text data using Natural Language Processing (NLP) techniques.
The goal is to classify each tweet as Positive, Negative, or Neutral based on its content.

This project includes:

Text preprocessing

TF-IDF vectorization

Machine learning model

Evaluation and insights

📂 Dataset

Dataset used: Twitter US Airline Sentiment (Kaggle)
Columns used:

text – tweet content

sentiment – label (positive/neutral/negative)

🔧 Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib

Seaborn

NLP (TF-IDF, text cleaning)

🧹 Steps Performed
1. Data Preprocessing

Lowercasing

Removing links, mentions, special characters

Token cleaning

2. Feature Extraction

Converting text to numerical vectors using TF-IDF

3. Model Training

Logistic Regression model

Train–test split

4. Model Evaluation

Accuracy score

Classification report

Predicting sentiment on new text

5. Data Visualization

Sentiment distribution chart

📊 Results

Achieved good accuracy using Logistic Regression

Negative tweets were the most frequent

Words like “delay”, “cancelled” show negative emotion

Words like “awesome”, “great”, “thank you” show positive sentiment

🚀 How to Run the Notebook

Open the Google Colab notebook

Upload the dataset

Run all cells in order

📎 Output

Cleaned dataset

TF-IDF vectors

Sentiment classification model

Evaluation metrics

Visual insights.

