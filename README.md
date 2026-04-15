# Sentiment_Analysis_Amazon_Reviews
Sentiment Analysis for amazon reviews

## 📌 Project Overview
This project focuses on analyzing customer reviews to determine whether the sentiment is **positive** or **negative**.  
It uses Natural Language Processing (NLP) techniques and Machine Learning models to classify text data.

---

## 📊 Dataset
- Dataset used: **IMDb Reviews / Amazon Product Reviews (Kaggle)**
- The dataset contains user reviews labeled as **positive** or **negative**

---

## ⚙️ Project Pipeline

### 1. Text Preprocessing
- Convert text to lowercase  
- Remove stopwords  
- Clean unnecessary characters  

### 2. Feature Engineering
- Convert text into numerical representation using **TF-IDF**

### 3. Model Training
Two models were trained and evaluated:
- Naive Bayes  
- Logistic Regression  

---

## 📈 Model Performance

### 🔹 Naive Bayes

Accuracy: 92%

Negative:
Precision: 0.98 | Recall: 0.62 | F1-score: 0.76

Positive:
Precision: 0.91 | Recall: 1.00 | F1-score: 0.95


---

### 🔹 Logistic Regression

Accuracy: 97%

Negative:
Precision: 0.89 | Recall: 1.00 | F1-score: 0.94

Positive:
Precision: 1.00 | Recall: 0.97 | F1-score: 0.98


---

## 🧠 Key Insights
- Logistic Regression outperformed Naive Bayes in overall accuracy and balance  
- Naive Bayes struggled with detecting negative reviews (lower recall)  
- TF-IDF proved effective for text feature representation  

---

## 🚀 Technologies Used
- Python  
- Scikit-learn  
- Pandas  
- NumPy
- NLTK
- contractions


---

## 📌 Conclusion
This project demonstrates how NLP techniques combined with machine learning models can effectively classify customer sentiment and provide valuable insights for businesses.

---

## 🔗 Future Improvements
- Use deep learning models (LSTM / Transformers)  
- Handle class imbalance more effectively  
- Deploy the model as a web application  
