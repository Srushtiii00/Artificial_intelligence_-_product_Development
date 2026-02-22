# 📩 SMS Spam Detection using Machine Learning

## 📖 Project Overview
This project focuses on detecting spam messages using machine learning techniques.  
The model analyzes SMS text data and predicts whether a message is **spam** or **ham (not spam)**.

The goal is to apply Natural Language Processing (NLP) and classification algorithms to build an accurate spam detection system.

---

## 🎯 Objectives

- Load and explore SMS dataset
- Perform text preprocessing and cleaning
- Convert text into numerical features
- Train machine learning models for spam detection
- Evaluate model performance

---

## 📂 Dataset

The project uses the **SMSSpamCollection dataset** containing:

- **Label** → Spam or Ham
- **Text** → SMS message content

---

## ⚙️ Methodology

### ✅ Data Preprocessing
- Remove unwanted characters
- Convert text to lowercase
- Remove stopwords
- Apply stemming using Porter Stemmer

### ✅ Feature Extraction
- Convert text data into numerical format for model training.

### ✅ Model Training
The following models were used:

- Multinomial Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)

### ✅ Model Evaluation
Performance measured using:

- Accuracy
- Precision
- Recall

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** — data handling
- **NumPy** — numerical operations
- **NLTK** — text preprocessing
- **Scikit-learn** — machine learning models

---

## 🚀 How to Run

1. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn nltk