# Brainwave_Matrix_Intern
# Task 1: Fake News Detection Model

This task involves building a machine learning model to detect fake news articles using Natural Language Processing (NLP).

## Objective:
- Build a model that can classify news articles as either "REAL" or "FAKE" using a dataset of labeled news articles.
- The model should be trained using the PassiveAggressiveClassifier and evaluated for accuracy.

## Task Details:
- The dataset consists of two CSV files: `fake.csv` (fake news articles) and `true.csv` (real news articles).
- The script preprocesses the data, vectorizes the text using `TfidfVectorizer`, and trains a machine learning model.
- The model's performance is evaluated based on accuracy and confusion matrix metrics.

## Repository:
The code for this task can be found in the `fake-news-detector` repository. You can access the repository at the following link:

[Fake News Detector Repository](https://github.com/MhamedHalloub/fake-news-detector)

## Steps:
1. Download the dataset files (`fake.csv` and `true.csv`).
2. Install the required libraries:
   ```bash
   pip install pandas scikit-learn nltk
