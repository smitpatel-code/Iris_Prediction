# 🌸 Iris Flower Classification - Machine Learning Project

This project demonstrates a complete Machine Learning pipeline for multiclass classification using the famous Iris dataset. The objective is to predict the species of an iris flower based on its physical measurements.

---

## 📌 Project Overview

This project includes:

- Data loading and preprocessing
- Feature scaling using StandardScaler
- Train-test split with stratification
- Model training
- Hyperparameter tuning (GridSearchCV)
- Model evaluation using proper multiclass metrics

The dataset contains three classes:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

## 🤖 Models Implemented

1. Logistic Regression  
2. K-Nearest Neighbors (KNN)  
3. Naive Bayes  

For KNN, hyperparameter tuning was performed using GridSearchCV to find the optimal number of neighbors.

---

## 📊 Evaluation Metrics Used

Since this is a multiclass classification problem, the following metrics were used:

- Accuracy
- Precision (macro average)
- Recall (macro average)
- F1-Score (macro average)
- Confusion Matrix
- Cross-Validation Score

Macro averaging was used to ensure equal importance across all classes.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 🎯 Key Learnings

- Importance of feature scaling in distance-based models like KNN
- Proper evaluation of multiclass classification problems
- Hyperparameter tuning using GridSearchCV
- Preventing data leakage
- Using cross-validation for reliable model performance

---

## 📈 Results

The models achieved high accuracy due to the well-separated nature of the Iris dataset. This project demonstrates strong understanding of core machine learning concepts and evaluation techniques.

---

## 🚀 Future Improvements

- Add visualization of decision boundaries
- Compare additional models (SVM, Random Forest)
- Deploy as a web app using Streamlit
- Add model performance comparison plots

---

### ⭐ If you found this project useful, feel free to give it a star!
