# 🧠 Customer Churn Prediction using ANN

## 📌 Project Overview

This project focuses on building an Artificial Neural Network (ANN) to predict customer churn. The main goal was not just to build a model, but to deeply understand the complete pipeline of a deep learning project.

---

## 🎯 Objective

To predict whether a customer will churn (leave the service) based on various features such as usage patterns, billing information, and customer demographics.

---

## 📂 Dataset

* Telco Customer Churn Dataset
* Contains customer details, services used, and churn status

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

* Removed irrelevant columns (e.g., customerID)
* Handled data type issues (`TotalCharges`)
* Treated missing values logically
* Cleaned categorical inconsistencies

### 2. Feature Engineering

* Binary Encoding (Yes/No → 1/0)
* One-Hot Encoding for multi-category features
* Feature scaling using StandardScaler

### 3. Model Building (ANN)

* Sequential Neural Network
* Architecture:

  * Input Layer
  * Hidden Layers (Dense + ReLU)
  * Batch Normalization
  * Dropout for regularization
  * Output Layer (Sigmoid)

### 4. Model Training

* Optimizer: Adam
* Loss Function: Binary Crossentropy
* EarlyStopping used to prevent overfitting

### 5. Evaluation

* Accuracy ≈ 81%
* Confusion Matrix
* Precision, Recall, F1-score

---

## 📊 Key Insights

* ANN performance is limited by dataset quality and feature strength
* Class imbalance significantly affects accuracy
* Feature engineering has more impact than model complexity

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib

---

## 💡 Learning Outcome

This project helped me understand:

* End-to-end ANN workflow
* Importance of preprocessing
* Model evaluation beyond accuracy
* Practical challenges in real-world datasets

---

## 📌 Author

Faseeh – Data Science Enthusiast
