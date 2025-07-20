# NLP-Assignment

# 🧠 Text Classification using Traditional NLP & ML

This project implements a complete **text classification pipeline** using traditional NLP techniques and classical machine learning models. The goal is to classify text data into categories using different feature extraction methods (BoW, TF-IDF, Word2Vec) and classifiers (Naive Bayes, Logistic Regression, SVM).

---

## ⚙️ Setup

1. Clone the repository or open the notebook in Google Colab.
2. Install required packages:
   ```bash
   pip install -r requirements.txt


3. Run text_classification_pipeline.ipynb step-by-step:

✅ Preprocess text data

✅ Extract features using BoW, TF-IDF, and Word2Vec

✅ Train models: Naive Bayes, Logistic Regression, SVM

✅ Evaluate using accuracy, precision, recall, F1-score

✅ Visualize results with confusion matrices and bar plots


📊 Results Summary
Feature + Model	Accuracy	F1 Score (Macro)
BoW + Naive Bayes	0.953	0.908
TF-IDF + Logistic Regression	0.947	0.862
Word2Vec + Logistic Regression	0.866	0.464
TF-IDF + SVM	0.979	0.952

🔝 Best performing model: TF-IDF + SVM
📉 Lowest performance: Word2Vec + Logistic Regression
