# 📧 Email Spam Classification using Machine Learning

## 📌 Project Overview

This project builds a **Machine Learning model to classify emails/messages as Spam or Ham (Not Spam)**.
Spam detection is widely used in email services to automatically filter unwanted or promotional messages.

The model learns patterns from text messages and predicts whether a new message is **spam or not spam**.

---

## 🎯 Problem Statement

Many users receive unwanted emails or SMS messages such as advertisements, scams, or phishing attempts.
The goal of this project is to **build a machine learning model that automatically detects spam messages**.

---

## 📊 Dataset

The project uses the **SMS Spam Collection Dataset**.

The dataset contains two main columns:

| Column   | Description          |
| -------- | -------------------- |
| Category | Label (Spam or Ham)  |
| Message  | Text message content |

Example:

| Category | Message                                            |
| -------- | -------------------------------------------------- |
| ham      | Ok lar joking wif u oni                            |
| spam     | Free entry in 2 a weekly competition to win FA Cup |

---

## ⚙️ Technologies Used

* Python
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* Natural Language Processing (NLP)

---

## 🧠 Machine Learning Approach

### 1️⃣ Data Preprocessing

* Removing unnecessary columns
* Renaming columns
* Converting labels to numeric values

### 2️⃣ Text Vectorization

Text data is converted into numerical form using:

**TF-IDF Vectorization**

This helps the model understand the importance of words in messages.

### 3️⃣ Model Training

The model is trained using **Logistic Regression** to classify messages.

### 4️⃣ Model Evaluation

Performance is evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report

---

## 📈 Model Performance

The model achieves approximately:

**Accuracy: ~97%**

This means the model correctly classifies most spam and normal messages.

---

## 🚀 Example Prediction

Input Message:

"Congratulations! You won a free lottery ticket."

Model Prediction:

Spam Message

---

## 📂 Project Structure

```
Email-Spam-Classification
│
├── email_classification.ipynb
├── spam.csv
└── README.md
```

---

## 💡 Future Improvements

* Use advanced NLP techniques
* Train deep learning models
* Build a web interface using Streamlit
* Deploy the model as an API

---

## 👩‍💻 Author

Swathi Ravi
Artificial Intelligence & Machine Learning Student
