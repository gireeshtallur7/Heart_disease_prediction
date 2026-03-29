# ❤️ Heart Disease Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.0+-red.svg)
![Accuracy](https://img.shields.io/badge/Accuracy-86%25-brightgreen.svg)

## 📌 Overview

This project predicts the likelihood of heart disease in patients using **Supervised Machine Learning** algorithms. Built with **Python** and **Scikit-learn**, the model achieves **86% accuracy** using Logistic Regression, outperforming SVM, Decision Tree, and Naïve Bayes.

## 🎯 Key Features

- ✅ **4 Supervised Algorithms** compared (Logistic Regression, SVM, Decision Tree, Naïve Bayes)
- ✅ **86% Accuracy** with Logistic Regression after hyperparameter tuning
- ✅ **Interactive Web App** built with Streamlit for real-time predictions
- ✅ **5-Fold Cross Validation** for robust model evaluation
- ✅ **ROC-AUC Score: 0.91** demonstrating strong discriminatory power

## 🏥 Problem Statement

Cardiovascular diseases are the leading cause of death globally. Early detection can save lives. This project helps medical professionals assess heart disease risk based on patient clinical parameters.

## 📊 Dataset

The dataset contains **14 clinical features**:

| Feature | Description |
|---------|-------------|
| age | Age in years |
| sex | 1 = male, 0 = female |
| cp | Chest pain type (0-3) |
| trestbps | Resting blood pressure (mm Hg) |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| restecg | Resting ECG results (0-2) |
| thalach | Maximum heart rate achieved |
| exang | Exercise induced angina (1 = yes, 0 = no) |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels (0-3) |
| thal | Thalassemia (0-3) |
| target | 0 = no disease, 1 = disease |

## 🧠 Algorithms Implemented

| Algorithm | Accuracy |
|-----------|----------|
| **Logistic Regression** | **86%** ✅ |
| Support Vector Machine (SVM) | 83% |
| Decision Tree | 78% |
| Naïve Bayes | 81% |

## 🛠️ Technologies Used
Python 3.8+
Scikit-learn
Pandas & NumPy
Matplotlib & Seaborn
Streamlit
Joblib 
