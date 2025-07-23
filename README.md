# NLP-Assignment

# 🧠 Text Classification using Traditional NLP & ML

This project implements a complete **text classification pipeline** using traditional NLP techniques and classical machine learning models. The goal is to classify text data into categories using different feature extraction methods (BoW, TF-IDF, Word2Vec) and classifiers (Naive Bayes, Logistic Regression, SVM).

## 📌 Project Overview

Run the `NLP_Assignment.ipynb` notebook step-by-step:

1. **Preprocess** text data (lowercasing, tokenization, stopword removal, etc.)
2. **Extract Features** using:
   - Bag of Words (BoW)
   - TF-IDF
   - Word2Vec
3. **Train Models**:
   - Naive Bayes
   - Logistic Regression
   - Support Vector Machine (SVM)
4. **Evaluate Models** using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
5. **Visualize Results** using confusion matrices and bar plots

## ✅ Results Summary

| Feature + Model                 | Accuracy | F1 Score (Macro) |
|-------------------------------|----------|------------------|
| BoW + Naive Bayes             | 0.953    | 0.91            |
| TF-IDF + Logistic Regression  | 0.947    | 0.85           |
| Word2Vec + Logistic Regression| 0.866    | 0.464            |
| TF-IDF + SVM                  | 0.979    | 0.93            |



🔝 Best performing model: TF-IDF + SVM

📉 Lowest performance: Word2Vec + Logistic Regression
