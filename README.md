# 🕵️ Fake Review Detection System

Fake Review Detection System is a Machine Learning project that uses Natural Language Processing (NLP) and TF-IDF feature extraction to classify product reviews as Fake or Real. The model is trained using Logistic Regression (along with Random Forest and SVM for comparison) and deployed using Streamlit for real-time prediction.

This project detects whether a product review is Fake or Real using Machine Learning.

## 📌 Features
- TF-IDF Vectorization
- Logistic Regression
- Random Forest
- SVM
- Streamlit UI

## 🛠 Tech Stack
- Python
- Scikit-learn
- NLTK
- Streamlit
- Google Colab

## ▶️ Run in Colab
Open notebook and run all cells sequentially.
                ┌────────────────────┐
                │   Dataset (CSV)    │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Data Cleaning      │
                │ - Remove Null      │
                │ - Remove Duplicate │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Text Preprocessing │
                │ - Lowercase        │
                │ - Remove URL       │
                │ - Remove Symbols   │
                │ - Remove Stopwords │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ TF-IDF Vectorizer  │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ ML Model Training  │
                │ - Logistic Reg     │
                │ - Random Forest    │
                │ - SVM              │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Model Evaluation   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Model Saved (.pkl) │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Streamlit Web App  │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ User Input Review  │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Prediction Output  │
                │ Fake / Real        │
                └────────────────────┘
