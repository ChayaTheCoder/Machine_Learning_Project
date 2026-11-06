# Emotion and Sentiment Classification of Social Media Text

Authors: Michaya Mohamed, Ivan Ivanov

# Project Overview
This project explores machine learning techniques for emotion and sentiment classification using social media text data collected from Twitter. The dataset contains 20,000 labeled text samples representing six emotional categories:

# Label	Emotion
- 0	Sadness
- 1	Joy
- 2	Love
- 3	Anger
- 4	Fear
- 5	Surprise

Rather than replacing the original emotion labels, this project investigates how different sentiment analysis methods interpret emotional content as positive, negative, or neutral. The goal is to compare machine learning and rule-based sentiment models and evaluate how well they align with human interpretations of emotion expressed in social media text.

# Research Question
How effectively can different sentiment analysis algorithms classify emotional social media posts as positive, negative, or neutral?

# Dataset
- Source: Kaggle
- Data Type: Short form social media text

 # Dataset Split
- Original Classes: 6 emotions
- Training Samples: 16,000
- Validation Samples: 2,000
- Testing Samples: 2,000

# Algorithms
1. Logistic Regression serves as a strong baseline text classification model and performs well with TF-IDF features.

2. Support Vector Machine (SVM) is effective in high-dimensional text classification problems and is commonly used in sentiment analysis tasks.

3. Multinomial Naive Bayes is a probabilistic text classification model that performs efficiently on sparse text data.

4. VADER Sentiment Analyzer (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool designed specifically for social media text.

5. Dictionary-Based Scoring sentiment analysis uses predefined sentiment lexicons to calculate positive, negative, and neutral sentiment scores without model training.

# Methods
The text data will be preprocessed using standard natural language processing techniques including lowercasing, punctuation removal, stop-word removal, and TF-IDF vectorization. Machine learning models will be trained on the training set, tuned using the validation set, and evaluated on the testing set. Performance will be measured using accuracy, precision, recall, F1-score, and confusion matrices.

# Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
