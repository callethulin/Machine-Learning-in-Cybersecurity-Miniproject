# Machine-Learning-in-Cybersecurity-Miniproject

# 🛡️ LLM-Generated Phishing Email Detection

## 📌 Project Overview
This project was conducted as part of the *EIE4121 Machine Learning in Cyber-security* course. The objective is to investigate whether machine learning techniques can distinguish between **human-written** and **LLM-generated emails**.

The problem is formulated as a **classification task**, where the goal is to determine:
- Whether an email is **human-generated or LLM-generated**

---

## 📊 Dataset
The dataset used in this project is publicly available on Kaggle and consists of:

- 2000 human-generated emails (1000 legitimate, 1000 phishing)  
- 2000 LLM-generated emails (1000 legitimate, 1000 phishing)  

The LLM-generated emails were created using models such as ChatGPT and WormGPT.

---

## ⚙️ Methods Used

Two machine learning models were implemented and evaluated:

### Support Vector Machine (SVM)
- Implemented by **me**
- Used for classification of email text data  
- Effective in handling high-dimensional feature spaces  
- Includes preprocessing, feature extraction, model training, and evaluation  

### Logistic Regression
- Implemented by **group member**
- Used as a baseline linear classification model  
- Provides interpretable probabilistic outputs  
- Includes preprocessing, training, and evaluation  

---

## 🔍 Feature Engineering
Feature extraction was applied to the email text using standard NLP techniques:
- Text vectorization (e.g., TF-IDF)
- Basic preprocessing (tokenization, stopword removal, etc.)

The goal was to capture patterns that distinguish:
- Human vs LLM-generated text   

---

## 📈 Results & Comparison
Both models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-score  

### Key Observations
- The **SVM model** captured more complex patterns in the data  
- The **Logistic Regression model** provided a strong and interpretable baseline  
- There is a trade-off between model performance and interpretability  

---

## ⚠️ Limitations
- The dataset size is relatively limited  
- LLM-generated text is becoming increasingly realistic  
- More advanced NLP techniques could improve performance  

---

## 👥 Contributions

| Name | Contribution |
|------|------------|
| Me | Implemented and evaluated the SVM model |
| Group Member | Implemented and evaluated the Logistic Regression model |

