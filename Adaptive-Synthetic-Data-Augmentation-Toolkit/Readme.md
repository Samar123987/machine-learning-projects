# Adaptive Synthetic Data Augmentation Toolkit for Fraud Detection

## 📌 Overview
This project focuses on detecting credit card fraud using machine learning and improving model performance through adaptive synthetic data generation. It uses CTGAN to generate synthetic fraud samples and applies iterative retraining to improve model accuracy on imbalanced datasets.

---

## 🎯 Objective
- Detect fraudulent transactions using ML models
- Handle class imbalance problem
- Generate synthetic fraud data using CTGAN
- Improve model performance through iterative training
- Build an adaptive learning system

---

## 📊 Dataset Description
The dataset contains credit card transaction records including:
- Transaction Date
- Transaction Type
- Location
- Transaction Features
- Target Variable: IsFraud (0 = Non-Fraud, 1 = Fraud)

---

## ⚠️ Problem Statement
Fraud detection datasets are highly imbalanced, where fraud cases are significantly fewer than normal transactions. This leads to biased models.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- SDV (Synthetic Data Vault)
- CTGAN (Conditional Tabular GAN)

---

## 🔄 Methodology

### 1. Data Preprocessing
- Label encoding of categorical features
- Splitting dataset into features and target variable

### 2. Baseline Model
- Random Forest Classifier trained on original dataset
- Evaluation using confusion matrix and classification report

### 3. Synthetic Data Generation
- Minority class (fraud data) extracted
- CTGAN trained on fraud samples
- Synthetic fraud data generated

### 4. Data Augmentation
- Combined real + synthetic data
- Re-trained Random Forest model

### 5. Adaptive Learning (Iterative Training)
- Multiple iterations of:
  - Synthetic data generation
  - Model retraining
  - Performance evaluation

---

## 📈 Results
- Initial model suffers from class imbalance
- Synthetic data improves fraud detection capability
- Iterative training further enhances model performance
- Better recall for fraud class achieved after augmentation

---

## 💡 Key Insights
- Imbalanced datasets require specialized techniques
- Synthetic data generation improves minority class learning
- CTGAN is effective for tabular fraud data
- Iterative training creates adaptive ML systems

---

## 🚀 How to Run
1. Install dependencies:

2. Run notebook step by step:
- Load dataset
- Train baseline model
- Generate synthetic data
- Retrain model

---

## 👩‍💻 Author
This project was developed as part of an ML internship focusing on fraud detection, synthetic data generation, and adaptive machine learning systems.