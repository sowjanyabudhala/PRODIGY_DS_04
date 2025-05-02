# 🍽️ Restaurant Reviews Classification using NLP

This project focuses on classifying restaurant reviews into **positive** or **negative** sentiments using Natural Language Processing (NLP). By analyzing customer reviews, we aim to help restaurants and aggregators understand customer feedback and improve service quality.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Visualizations](#visualizations)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)
  

---

## 📖 Project Overview

Online restaurant reviews are a goldmine of customer opinions. This project uses **text classification** techniques to predict whether a given restaurant review expresses a positive or negative sentiment.

---

## 🎯 Objectives

- Preprocess and clean review text data.
- Convert text into numerical features using techniques like **Bag of Words** or **TF-IDF**.
- Train and evaluate classification models such as **Naive Bayes**, **Logistic Regression**, or **SVM**.
- Measure model performance and interpret results.
- Deploy insights through visualizations.

---

## 📂 Dataset

- The dataset contains **textual restaurant reviews** labeled with sentiment.
- Features:
  - `Review`: The actual text of the review.
  - `Liked`: Target label (1 = Positive, 0 = Negative)

> ⚠️ If your dataset is sourced from a specific site or repository, include the citation or link here.

---

## 🧰 Technologies Used

| Category           | Tools/Libraries                         |
|--------------------|-----------------------------------------|
| Language           | Python 3.x                              |
| IDE                | Jupyter Notebook                        |
| Data Manipulation  | Pandas, NumPy                           |
| NLP                | NLTK, re (Regex), Scikit-learn          |
| Visualization      | Matplotlib, Seaborn, WordCloud          |
| Modeling           | Naive Bayes, Logistic Regression, SVM   |
| Feature Extraction | CountVectorizer, TfidfVectorizer        |

---

## 🧹 Data Preprocessing

- Lowercasing the text
- Removing punctuation, numbers, and stopwords
- Tokenization
- Lemmatization/Stemming
- Feature extraction via **Bag of Words** or **TF-IDF**

---

## 🤖 Modeling

Trained classification models:
- **Multinomial Naive Bayes**
- **Logistic Regression**
- (Optional: **SVM**, **Random Forest**)

Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📊 Visualizations

- WordClouds of positive vs. negative reviews


---


## 🗂️ Project Structure
restaurant-reviews-classification/
│
├── Restaurant_reviews_classification.ipynb 
├── requirements.txt                          
├── README.md                                 
└── dataset

## 🔮 Future Improvements
Use more advanced NLP models like BERT or RoBERTa.

Include a neutral sentiment class.

Build a web app with Streamlit or Flask.

Deploy the model with an API for real-time classification.



