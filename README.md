# Smart-Retail-Customer-Intelligence-Platform
AI-Powered Smart Retail &amp; Customer Intelligence Platform using Computer Vision, NLP, FastAPI, and Machine Learning.
# 🛍️ AI-Powered Smart Retail Customer Intelligence Platform

## 📖 Project Overview

The **AI-Powered Smart Retail Customer Intelligence Platform** is an intelligent retail application that combines multiple Artificial Intelligence modules into a single system. It helps retail stores recognize customers, classify products, analyze customer reviews, and provide automated customer support.

This project is developed using **Python, TensorFlow, Scikit-learn, FastAPI, OpenCV, and Google Colab**.

---

# 🚀 Features

- 👤 Customer Face Recognition *(In Progress)*
- 🛒 Product Image Classification
- 💬 Customer Review Sentiment Analysis
- 🤖 AI Retail Chatbot *(In Progress)*
- 🌐 FastAPI Backend *(In Progress)*

---

# 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- Scikit-learn
- TF-IDF
- Logistic Regression
- OpenCV
- FastAPI
- Google Colab
- GitHub

---

# 📂 Project Structure

```
Smart-Retail-Customer-Intelligence-Platform/
│
├── app/
├── data/
├── docs/
├── images/
├── models/
│   ├── product_classifier.h5
│   ├── sentiment_model.pkl
│   └── vectorizer.pkl
│
├── notebooks/
│   ├── 01_Product_Classifier.ipynb
│   └── 02_Sentiment_Analysis.ipynb
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# 📌 Module 1 – Product Image Classification

### Objective

To classify retail product images into different product categories using Deep Learning.

### Dataset

Fashion Product Images Dataset (Kaggle)

### Model

- MobileNetV2 (Transfer Learning)

### Workflow

```
Product Image
      │
      ▼
Image Preprocessing
      │
      ▼
MobileNetV2
      │
      ▼
Product Category Prediction
```

### Output

- Trained model: `product_classifier.h5`

### Status

✅ Completed

---

# 📌 Module 2 – Customer Review Sentiment Analysis

### Objective

To classify customer reviews into Positive, Neutral, and Negative sentiments using Natural Language Processing (NLP).

### Dataset

Women's Clothing E-Commerce Reviews (Kaggle)

### Model

- TF-IDF Vectorizer
- Logistic Regression

### Workflow

```
Customer Review
      │
      ▼
Text Cleaning
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Logistic Regression
      │
      ▼
Positive / Neutral / Negative
```

### Model Performance

- Accuracy: **76.5%**

### Output

- `sentiment_model.pkl`
- `vectorizer.pkl`

### Status

✅ Completed

---

# 🚧 Upcoming Modules

### Module 3

👤 Face Recognition

### Module 4

🤖 Retail Chatbot

### Module 5

⚡ FastAPI Integration

---

# 📊 Current Project Progress

| Module | Status |
|---------|--------|
| Product Classification | ✅ Completed |
| Sentiment Analysis | ✅ Completed |
| Face Recognition | 🔄 In Progress |
| Retail Chatbot | 🔄 In Progress |
| FastAPI Integration | 🔄 Pending |

---

# 👩‍💻 Author

**Disha Gupta**

Integrated M.Tech – CSE (Computational Data Science)

---

# 📜 License

This project is developed for academic and educational purposes.
