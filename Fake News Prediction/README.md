# Fake News Prediction

## Overview

With the rapid growth of digital media, **fake news detection** has become a critical challenge. Misleading or false information can spread quickly online, influencing opinions, decisions, and even elections.  

This project builds a **machine learning model** to classify news articles as **real or fake** using **Logistic Regression**. By analyzing the text of articles, the model learns patterns that distinguish between trustworthy and deceptive content.

---

## Project Objectives

- Develop a supervised learning model to detect fake news  
- Apply **Natural Language Processing (NLP)** techniques for text cleaning and feature extraction  
- Evaluate the performance of Logistic Regression for binary text classification  

---

## Workflow

1. **Data Collection**  
   Used a labeled dataset containing news articles marked as *real* or *fake*.  

2. **Data Preprocessing**  
   - Removed stopwords, punctuation, and irrelevant characters  
   - Applied tokenization and stemming/lemmatization  
   - Converted text into numerical representations using **TF-IDF vectorization**  

3. **Model Training**  
   - Trained a **Logistic Regression classifier** on the processed dataset  
   - Used train-test split to evaluate model generalization  

4. **Evaluation**  
   - Metrics: **Accuracy, Precision, Recall, F1-score, Confusion Matrix**  
   - Assessed strengths and weaknesses of the model in distinguishing fake vs. real news  

---

## Results

- The **Logistic Regression** model achieved high accuracy in classifying news articles.  
- The model effectively captured patterns in word usage and style that correlate with fake news.  
- **Limitations**: Struggles with nuanced cases (e.g., satire or partially true content).  

---

## Key Learnings

- Logistic Regression is simple yet powerful for binary classification tasks

- Text preprocessing and feature engineering significantly affect model performance

- Fake news detection remains a complex challenge requiring continual updates with new data
