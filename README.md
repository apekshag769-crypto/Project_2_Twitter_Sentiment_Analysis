# Twitter Sentiment Analysis Using NLP and Machine Learning

## Project Overview
This project focuses on analyzing Twitter data and classifying tweets into three sentiment categories: Positive, Negative, and Neutral using Natural Language Processing (NLP) and Machine Learning.

## Objectives
- Analyze Twitter text data.
- Clean and preprocess tweets.
- Extract important text features.
- Build a sentiment classification model.
- Evaluate model performance.

## Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib

## Dataset
The project uses the TweetEval Sentiment Dataset from Cardiff NLP.

The dataset contains three sentiment labels:
- 0 – Negative
- 1 – Neutral
- 2 – Positive

## Methodology

### 1. Data Collection
Loaded Twitter sentiment data using the Hugging Face Datasets library.

### 2. Text Preprocessing
- Converted text into lowercase.
- Removed URLs and mentions.
- Removed special characters.
- Removed stopwords.
- Cleaned unnecessary spaces.

### 3. Feature Extraction
Used TF-IDF (Term Frequency–Inverse Document Frequency) to convert text into numerical features.

### 4. Model Training
Implemented Logistic Regression to classify tweets into sentiment categories.

### 5. Model Evaluation
Evaluated the model using:
- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Output
The model predicts whether a given tweet expresses Positive, Negative, or Neutral sentiment.

## Project Files
- CodeTech_Twitter_Sentiment_Analysis.ipynb
- twitter_sentiment_dataset.csv
- sentiment_predictions.csv

## Conclusion
This project demonstrates how Natural Language Processing and Machine Learning can be used to understand opinions and emotions expressed in Twitter data.

## Disclaimer
This project is developed for educational purposes as part of the CodeTech Technologies internship.
