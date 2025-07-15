# 📧 Spam Classifier

A machine learning project that classifies SMS messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) and Scikit-learn. The model is deployed using **Streamlit** for interactive use.

## 🔍 Project Overview

This project demonstrates how to build a text classification model using Python. It includes the following steps:

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Text vectorization using CountVectorizer and TF-IDF
- Model training using Naive Bayes
- Web application using Streamlit

## 📂 Dataset

The dataset used is the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset), which contains 5,572 labeled messages.

- **ham** = Not spam
- **spam** = Unwanted or harmful messages

## 🧪 Libraries Used

- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for visualization
- `scikit-learn` for model building
- `nltk` for NLP preprocessing
- `streamlit` for app deployment

## 📊 Exploratory Data Analysis

Performed EDA to understand:

- Class distribution
- Word frequency in spam vs ham messages
- Common keywords in spam messages
- Message length distributions

## 🧹 Preprocessing

Applied several NLP techniques including:

- Lowercasing
- Tokenization
- Removing stopwords
- Stemming using NLTK’s PorterStemmer

## 🤖 Model Building

Trained multiple models using Scikit-learn, including:

- Multinomial Naive Bayes (final model)
- Logistic Regression (for comparison)
- Support Vector Machine (for comparison)

Model evaluation metrics:

- Accuracy
- Precision
- Confusion Matrix

## 🖥️ Streamlit App

A simple and intuitive web interface where users can enter an SMS and get instant predictions.

### Run the app locally:

```bash
streamlit run app.py
