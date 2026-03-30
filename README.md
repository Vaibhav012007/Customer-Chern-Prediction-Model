# 📉 Customer Churn Prediction System

A deep learning-based customer churn prediction system that identifies customers likely to leave a service using structured data and neural networks.

---

## 📌 Overview

Customer churn is a major challenge for subscription-based businesses. This project builds a predictive model using a neural network to identify customers at risk of leaving, enabling proactive retention strategies.

---

## 🚀 Features

- End-to-end machine learning pipeline  
- Data preprocessing and feature engineering  
- One-hot encoding for categorical variables  
- Feature scaling for numerical stability  
- Neural network model using TensorFlow/Keras  
- Dropout regularization to prevent overfitting  

---

## 🧠 Model Architecture

- Input Layer: 11 features  
- Dense Layer: 32 neurons (ReLU activation)  
- Dropout Layer  
- Dense Layer: 16 neurons (ReLU activation)  
- Dropout Layer  
- Output Layer: 1 neuron (Sigmoid activation)  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Handling missing values  
- Encoding categorical variables using OneHotEncoder  
- Feature scaling using StandardScaler  

### 2. Model Training
- Neural network implemented using Keras  
- Loss function: Binary Cross-Entropy  
- Optimizer: Adam  

### 3. Regularization
- Dropout layers added to reduce overfitting  

---

## 📊 Model Performance

- **Accuracy**: 86.35%  
- **Precision**: 0.56  
- **Recall**: 0.72  

## 📊 Confusion Matrix

|                | Predicted No | Predicted Yes |
|----------------|-------------|---------------|
| Actual No      | 1496        | 89            |
| Actual Yes     | 184         | 231           |

### Interpretation

- High recall ensures most churners are correctly identified  
- Moderate precision indicates some false positives  
- Model prioritizes identifying churners, which is critical in business scenarios  

---

## 📂 Dataset

- Telco Customer Churn Dataset  
🔗 https://www.kaggle.com/datasets/blastchar/telco-customer-churn  

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
pip install -r requirements.txt
