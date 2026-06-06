# ML Model Comparison and Evaluation System

## 📌 Overview
This project focuses on building and comparing multiple machine learning models on a structured dataset to predict social media post engagement levels. The goal is to evaluate different algorithms and identify the best performing model using standard evaluation metrics.

---

## 🎯 Objective
- Predict engagement level of social media posts (Low, Medium, High)
- Compare multiple machine learning models
- Evaluate models using accuracy and classification metrics
- Analyze model performance for real-world decision making

---

## 📊 Dataset Description
The dataset contains social media post-related features such as:
- Post length
- Views
- Likes
- Comments
- Shares
- Platform (Instagram, Twitter, etc.)
- Post type (Text, Video, etc.)

The target variable is:
- **engagement_level** (Low, Medium, High)

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Data Preprocessing
- Handled missing values
- Converted engagement rate into categorical labels
- Applied One-Hot Encoding for categorical variables
- Applied Label Encoding for target variable
- Scaled features using StandardScaler

---

## 🤖 Machine Learning Models Used

The following models were trained and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes

---

## 📈 Evaluation Metrics
Each model was evaluated using:
- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 📊 Model Comparison
All models were compared visually using a bar chart based on accuracy scores.

The comparison helps in identifying which model performs best for predicting engagement levels.

---

## 🧠 Key Observations
- Ensemble methods like Random Forest generally perform better than simple models.
- SVM performs well in high-dimensional feature spaces.
- KNN is sensitive to feature scaling.
- Logistic Regression provides a strong baseline model.

---

## 🔮 Prediction System
The trained models can predict engagement level for new social media posts based on input features such as:
- Post length
- Views
- Likes
- Comments
- Shares
- Platform
- Post type

---

## 🚀 How to Run the Project
1. Open the Jupyter Notebook file
2. Install required libraries:
3. Run all cells sequentially
4. Test predictions using new input data section

---

## 👩‍💻 Author
This project was developed as part of an ML internship training program to practice model comparison and evaluation techniques in machine learning.