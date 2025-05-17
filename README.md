# Decoding Emotion through Sentiment Analysis of Social Media Conversations

This project focuses on analyzing social media text to detect the underlying emotion using machine learning. It uses natural language processing (NLP) to clean, transform, and extract features from social posts and classify them into emotions like happy, sad, angry, and others.

We trained and compared multiple models such as Random Forest, Logistic Regression, and Support Vector Machine. The Random Forest model performed best and was selected for deployment.

## Dataset

- Source:  https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset
- Features: `content` (text), `sentiment` (emotion label)
- Format: CSV

## Features

- Clean and preprocess text (remove mentions, links, punctuations)
- Extract features using TF-IDF
- Model training and evaluation
- Save the best model using `joblib`
- Deploy using Gradio

## live preview
- link: https://4f6d47c501e6bbf911.gradio.live

