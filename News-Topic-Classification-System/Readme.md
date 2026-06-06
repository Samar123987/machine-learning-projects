# News Topic Classification System Using Machine Learning

## 📌 Overview
This project focuses on classifying news articles into different categories using Natural Language Processing (NLP) and Machine Learning techniques. The system uses TF-IDF for feature extraction and compares multiple ML models for classification.

## 📊 Dataset
The dataset contains news articles and their corresponding categories. Each record includes:
- news_article (text)
- news_category (target label)

## 🎯 Objective
- Clean and preprocess text data
- Convert text into numerical features using TF-IDF
- Train multiple ML models for classification
- Compare model performance

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

## 🔍 Methodology

### 1. Data Preprocessing
- Removed special characters and numbers
- Converted text to lowercase
- Cleaned news articles for better processing

### 2. Feature Extraction
- Used TF-IDF Vectorizer
- Converted text into numerical feature vectors

### 3. Model Training
Two machine learning models were trained:
- Naive Bayes (MultinomialNB)
- Support Vector Machine (LinearSVC)

### 4. Evaluation
Models were evaluated using:
- Accuracy Score
- F1 Score
- Confusion Matrix

### 5. Model Comparison
Performance of both models was compared using bar charts for accuracy and F1-score.

## 📈 Results
- Both models performed well on text classification
- SVM generally provides better performance for high-dimensional text data
- Naive Bayes is fast and efficient for baseline comparison

## 📊 Visualization
Includes:
- Confusion Matrix for both models
- Accuracy vs F1-score comparison chart

## 🚀 How to Run
1. Open notebook.ipynb in Jupyter Notebook or VS Code
2. Install required libraries:
3. Run all cells sequentially

## 👩‍💻 Author
This project was completed as part of ML internship experience and NLP learning journey.