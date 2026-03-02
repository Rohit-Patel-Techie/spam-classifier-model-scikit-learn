# 📧 Email Spam Detection using Machine Learning  

A **Machine Learning project** that classifies emails as **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** techniques with **TF-IDF Vectorization**, **Logistic Regression**, and **Multinomial Naive Bayes**.

---

## 🚀 Project Overview  

This project builds a **text classification model** to automatically detect whether an email is spam or not spam using:

- ✅ Text Preprocessing  
- ✅ TF-IDF Vectorization  
- ✅ Logistic Regression  
- ✅ Multinomial Naive Bayes  
- ✅ Model Evaluation:
  - Accuracy Score  
  - Classification Report  
  - Confusion Matrix  

---

## 📂 Dataset  

This project uses the **Enron Spam Dataset**.

**GitHub Dataset Source:**  
👉 https://github.com/MWiechmann/enron_spam_data  

**Direct Download Link:**  
👉 https://github.com/MWiechmann/enron_spam_data/blob/master/enron_spam_data.zip  

### 📊 Dataset Columns  

| Column Name | Description |
|------------|-------------|
| Message ID | Unique email ID |
| Subject | Email subject line |
| Message | Email body |
| Spam/Ham | Target label (spam or ham) |
| Date | Email timestamp |

### 🎯 Target Encoding  

0 → Ham (Not Spam)
1 → Spam


---

## 🛠 Tech Stack  

- 🐍 Python  
- 📊 Pandas  
- 🔢 NumPy  
- 🤖 Scikit-learn  
- 📈 Matplotlib  
- 📉 Seaborn  
- 📓 Jupyter Notebook  

---

## 📦 Installation  

### 1️⃣ Clone the Repository  
- git clone https://github.com/Rohit-Patel-Techie/spam-classifier-model-scikit-learn.git
- cd email-spam-detection


### 2️⃣ Create Virtual Environment (Optional but Recommended)  

**Windows:**
- python -m venv venv
- venv\Scripts\activate

### 3️⃣ Install Dependencies  
- pip install -r requirements.txt

---

## ▶️ How to Run  

1️⃣ Place the dataset CSV file inside:
 
 data/email_spam_data.csv

2️⃣ Open Jupyter Notebook

3️⃣ Run all cells in the notebook.

---

## 📈 Model Evaluation Metrics  

- ✔ Accuracy Score  
- ✔ Precision  
- ✔ Recall  
- ✔ F1-Score  
- ✔ Confusion Matrix Visualization  

---

## ⭐ If you like this project  

Give it a ⭐ on GitHub and feel free to contribute! 🚀