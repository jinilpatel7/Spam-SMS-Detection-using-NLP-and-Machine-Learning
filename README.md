# Spam-SMS-Detection-using-NLP-and-Machine-Learning
Classify SMS as Spam or Ham using NLP and Machine Learning with 100% Precision

## 📌 Project Overview
Spam detection is a **text classification problem** where we classify SMS messages as **spam** (unwanted) or **ham** (legitimate). In this project, we use **Natural Language Processing (NLP) techniques** and **Machine Learning (ML) models** to detect spam messages efficiently.

---

## 📊 Dataset
We use a publicly available **Spam/Ham SMS dataset** in CSV format. The dataset contains:
- **label** → (Spam or Ham)
- **message** → (Text of the SMS)

---

## 🚀 Project Workflow

1️⃣ **Data Collection** → Load dataset from CSV file.

2️⃣ **Data Preprocessing** → Clean text, tokenize, remove stopwords, and apply lemmatization.

3️⃣ **Word Representation** → Convert text into numerical form using **TF-IDF Vectorization**.

4️⃣ **Model Building** → Train and evaluate different ML models.

5️⃣ **Model Evaluation** → Use accuracy, confusion matrix, and precision score.

---

## 🔄 Data Preprocessing Techniques  
✔ **Text Cleaning** → Remove special characters, numbers, and punctuation.  
✔ **Tokenization** → Split text into individual words.  
✔ **Stopword Removal** → Remove common words (e.g., "the", "is", "and").  
✔ **Lemmatization** → Convert words to their base form (e.g., "running" → "run").  

---

## 🔡 Word Representation  
We use **TF-IDF (Term Frequency-Inverse Document Frequency)** to transform text into numerical format suitable for ML models.

---

## 🤖 Machine Learning Models Used  
✔ **Multinomial Naïve Bayes** → Probabilistic classifier, best for text classification.  
✔ **Logistic Regression** → Works well with high-dimensional text data.  
✔ **Support Vector Machine (SVM)** → Effective for binary classification problems.  

---

## 📈 Model Evaluation  
We evaluate our models using:

✅ **Accuracy Score** → Measures overall correctness.  
✅ **Confusion Matrix** → Shows correct and incorrect classifications.  
✅ **Precision Score** → Measures how many predicted **spam messages** were actually spam.  

### 🎯 Best Model Performance:
🔹 **Precision Score: 1.0 (100% Precision in Spam Detection!)**  

---
