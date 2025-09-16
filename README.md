# Project 3: Spam Mail Detection using Machine Learning

This project is a simple binary classification model to predict whether an email is spam or not based on its content. It uses a machine learning classifier trained on text features extracted from the email dataset.

---

## Dataset

- Source: Publicly available Spam Mail Dataset (e.g., UCI ML Repository or Kaggle)  
- Features: Email text (converted into numerical features using techniques like TF-IDF or Count Vectorizer)  
- Target:  
  - `0` for Non-Spam (Ham)  
  - `1` for Spam  

---

## Model Used

- Algorithm: Naive Bayes Classifier (MultinomialNB)  
- Purpose: Binary classification (Spam vs Non-Spam)  
- Libraries: `scikit-learn`, `pandas`, `numpy`  

---

## Performance

| Metric             | Score   |
|---------------------|---------|
| Training Accuracy   | ~97%    |
| Testing Accuracy    | ~96%    |

*(Accuracy may vary depending on preprocessing and dataset split)*

---

## Run the Script

- Open `spam_detection.py` in your IDE or run in terminal  
- Input an email text to get prediction output  
- Output:  
  - `The mail is spam`  
  - `The mail is not spam`  

---

## Key Concepts Covered

- Text preprocessing (cleaning, tokenization)  
- Feature extraction (TF-IDF, Count Vectorization)  
- Naive Bayes classifier training  
- Accuracy evaluation  

---

## Requirements

- Python 3.x  
- scikit-learn  
- pandas  
- numpy  

---

## About

Detect spam emails using machine learning.  

---
