# 🧠 NLP Project Collection  

A collection of **Natural Language Processing (NLP) projects** built with Python and Machine Learning. These projects focus on **text classification, sentiment analysis, fake news detection, and multi-label predictions**, showcasing end-to-end pipelines from **EDA → Feature Engineering → Model Building → Deployment**.  

![Python](https://img.shields.io/badge/Python-3.6+-blue.svg) ![Libraries](https://img.shields.io/badge/Libraries-nltk,_sklearn,_pandas,_numpy,_matplotlib,_seaborn-orange.svg) ![Dataset](https://img.shields.io/badge/Datasets-Kaggle%20%7C%20UCI-green.svg)

---

## 📌 Projects Included  

### 1. 📱 Spam SMS Classifier  
- Detects/classifies SMS as **Spam or Ham** using NLP.  
- Features like `word_count`, `contains_currency_symbol`, `contains_numbers`.  
- Models Used: **Multinomial Naive Bayes, Decision Tree, Random Forest (F1-Score: 0.994)**.  
- **Dataset:** [UCI SMS Spam Collection](https://www.kaggle.com/uciml/sms-spam-collection-dataset)  
- **Deployment:** [Spam SMS Detector Web App](https://spam-sms-detector.herokuapp.com/)  

---

### 2. 📰 Fake News Classification  
- Classifies news articles as **Real or Fake**.  
- Applied **TF-IDF Vectorization** and **word embeddings**.  
- Models Used: **Naive Bayes, Logistic Regression, Random Forest, XGBoost**.  
- **Dataset:** [Fake News Dataset on Kaggle](https://www.kaggle.com/c/fake-news)  
- Helps combat misinformation by **filtering fake news** from social media and news sources.  

---

### 3. 🎬 Movie Genre Classifier (Multi-label)  
- Predicts **multiple genres** for a movie based on its plot description.  
- Used **multi-label classification techniques** (One-vs-Rest, Binary Relevance).  
- Feature Engineering with **TF-IDF** and word embeddings.  
- **Models:** Logistic Regression, Random Forest, Deep Learning Models.  
- **Dataset:** [Movie Dataset from Kaggle](https://www.kaggle.com/datasets)  

---

### 4. 🍴 Sentiment Analysis of Restaurant Reviews  
- Analyzes customer reviews and predicts **Positive or Negative sentiment**.  
- NLP preprocessing: tokenization, stopword removal, lemmatization.  
- Models: **Naive Bayes, Random Forest, SVM**.  
- **Dataset:** [Restaurant Reviews Dataset](https://www.kaggle.com/datasets)  
- Helps restaurants **improve service quality** by analyzing customer feedback.  

---

### 5. 📈 Stock Market Sentiment Analysis  
- Analyzes financial news & tweets to determine **Bullish / Bearish / Neutral sentiment**.  
- Applied NLP techniques with **TF-IDF, Word2Vec, and FinBERT embeddings**.  
- Models: Logistic Regression, Random Forest, LSTMs.  
- **Dataset:** [Stock News Sentiment Dataset on Kaggle](https://www.kaggle.com/datasets)  
- Can be integrated into **trading strategies & investment decisions**.  

---

## 🔧 Common Workflow Across Projects  
1. **Data Cleaning** → Removing special characters, tokenization, stopword removal, lemmatization.  
2. **Exploratory Data Analysis (EDA)** → Checking class balance, plotting distributions.  
3. **Feature Engineering** → TF-IDF, embeddings, feature extraction (`word_count`, `symbols`, `numbers`).  
4. **Model Training & Evaluation** → Naive Bayes, Logistic Regression, Random Forest, SVM, XGBoost, Neural Networks.  
5. **Evaluation Metrics** → Accuracy, Precision, Recall, F1-Score, Confusion Matrix.  
6. **Deployment** → Flask/Streamlit Web Apps (Heroku/Render).  

---

## 📊 Example Results  

| Project | Best Model | F1-Score / Accuracy |
|---------|------------|----------------------|
| Spam SMS Classification | Random Forest | **0.994** |
| Fake News Detection |  Naive Bayes | **0.95+** |
| Movie Genre Classification | Logistic Regression (Multi-label) | **0.90+** |
| Restaurant Review Sentiment | Naive Bayes | **0.92+** |
| Stock Sentiment Analysis | Naive Bayes/Random Forest Classifier/Multinomial Naive Bayes | **0.93+** |

---

## 🚀 Tech Stack  
- **Languages:** Python  
- **Libraries:** pandas, numpy, nltk, sklearn, matplotlib, seaborn  
- **Deep Learning:** TensorFlow / Keras (for LSTMs, embeddings)  
- **Deployment:** Flask, Streamlit, Heroku  

---

## 🌟 Future Enhancements  
- Incorporate **transformer-based models** (BERT, RoBERTa, DistilBERT).  
- Build a **unified NLP Dashboard** to host all projects in one place.  
- Integrate with **real-time APIs** for live predictions (e.g., Twitter sentiment, news feeds).  

---

✨ **If you find this repository useful, don’t forget to star ⭐ it!**  
