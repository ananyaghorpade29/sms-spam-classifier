# 📩 SMS Spam Classifier

## 🚀 Project Overview
This project is a Machine Learning model that classifies SMS messages as **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP).

---

## 🧠 Problem Statement
Spam messages are a common issue in mobile communication and can lead to fraud and security risks. This project aims to automatically detect spam messages.

---

## 🛠 Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF (Text Vectorization)
- Logistic Regression

---

## ⚙️ Workflow

1. Data Loading  
2. Data Cleaning  
   - Lowercasing  
   - Removing punctuation  
   - Removing numbers  
3. Feature Extraction using TF-IDF  
4. Train-Test Split  
5. Model Training (Logistic Regression)  
6. Prediction  

---
## 💡 Example

Input:
"Congratulations! You won a lottery!!!"
“Can you send me the notes from today’s meeting?”

Output:
This is a Spam Message
This is a Ham Message 

---
## 🔮 Future Improvements
Deploy as web app (Streamlit)
Try advanced models (SVM, Random Forest)
Improve preprocessing

---
## 📊 Model Performance

Accuracy: 97%

---

## 📁 Dataset
SMS Spam Collection Dataset from Kaggle

---

## ▶️ How to Run

```bash
pip install pandas scikit-learn
