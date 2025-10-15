# Smart-SMS-Spam-Classifier
Smart-SMS-Spam-Classifier
A Text Mining–Based Machine Learning Project for Spam Detection
🧩 Overview

Smart-SMS-Spam-Classifier is a text mining–based machine learning project that predicts whether an SMS message is spam or not spam.
It applies text preprocessing, feature extraction, and classification techniques to analyze message content and detect unwanted texts effectively.

This project is ideal for Text Mining, as it involves key NLP operations such as tokenization, stopword removal, stemming, and frequency-based feature representation.

⚙️ Technologies Used

Python

scikit-learn

pandas

numpy

🎯 Features

📊 Data collection and cleaning

🔍 Text preprocessing and tokenization

📈 Exploratory Data Analysis (EDA)

🤖 Model building and evaluation

📂 Data Collection

The dataset used is the SMS Spam Collection Dataset from Kaggle, containing 5,500+ labeled messages (spam or not spam).
You can access it here: SMS Spam Collection Dataset – Kaggle

🧹 Data Cleaning and Preprocessing

Removed null and duplicate entries

Label-encoded the type column (spam / ham)

Converted text to lowercase

Removed stopwords, punctuation, and special characters

Applied stemming to normalize words

These preprocessing steps are fundamental in Text Mining, ensuring clean and uniform text for analysis.

📊 Exploratory Data Analysis

Performed to understand text patterns and distributions:

Analyzed word, character, and sentence counts

Created bar charts, pie charts, and heatmaps

Generated word clouds for spam and non-spam texts

Identified frequent words in spam messages

🤖 Model Building and Selection

Multiple machine learning algorithms were trained and compared:

Naive Bayes

Random Forest

K-Nearest Neighbors (KNN)

Decision Tree

Logistic Regression

Extra Trees Classifier

Support Vector Classifier (SVC)

The best-performing model achieved 100% precision, making it reliable for detecting spam messages.

💬 Summary

Smart-SMS-Spam-Classifier demonstrates core Text Mining concepts — from text cleaning and tokenization to model training and evaluation.
It serves as an excellent mini-project for Text Mining or NLP coursework, combining practical data analysis with intelligent spam detection.
