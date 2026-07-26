[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/D94-Q8ry)
# Financial News Sentiment Analysis using Word Embeddings and Transformers

## 📌 Project Overview

This project uses **NLP and Deep Learning** to analyze financial news and classify the sentiment into:

- Positive
- Neutral
- Negative

Different text embedding methods and ML models are compared to find the best model.

---

## 🎯 Objective

To build an AI-based system that understands financial news and predicts its sentiment automatically.

---

## 📂 Dataset

The dataset contains:

- Date
- News article text
- Stock details (Open, High, Low, Close)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow/Keras
- Gensim
- Sentence Transformers
- Matplotlib & Seaborn

---

## 🔎 Project Workflow

### 1. Data Analysis
- Loaded dataset
- Checked missing values and duplicates
- Performed EDA
- Converted date format

### 2. Text Embedding

**Word2Vec**
- Converts words into numerical vectors.
- Creates sentence vectors by averaging word embeddings.

**Sentence Transformer**
- Used `BAAI/bge-base-en-v1.5`
- Converts complete news articles into meaningful embeddings.

---

## 🤖 Models Built

1. **Word2Vec + Random Forest**
2. **Word2Vec + Neural Network**
3. **Sentence Transformer + Random Forest**
4. ⭐ **Sentence Transformer + Neural Network**

---

## 📊 Model Evaluation

Models were compared using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🏆 Final Model

**Selected Model: Sentence Transformer + Neural Network**

Flow:
