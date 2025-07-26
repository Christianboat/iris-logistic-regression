[![Python](https://img.shields.io/badge/python-3.10-blue)](https://www.python.org/) [![Build Status](https://github.com/<Christianboat>/iris-logistic-regression/actions/workflows/ci.yml/badge.svg)](https://github.com/<Christianboat>/iris-logistic-regression/actions)

# Iris Logistic Regression

A clean, modular pipeline to classify Iris flower species using Logistic Regression. All development and model training happens on Kaggle; results and artifacts are then published here.

---
## 📂 Project Structure
iris-logistic-regression/
├── data/
│ └── Iris.csv # Raw dataset
├── LICENSE
├── main.py # Entry point tying modules together
├── notebooks/
│ └── iris_exploration.ipynb # Kaggle Notebook exported
├── models/
│ ├── iris_logistic_model.joblib
│ └── scaler.joblib
├── requirements.txt
└── README.md # This file
---

## 🎨 Results
Sepal Length Distribution

Sample Classification Report
Accuracy: 0.967
               precision    recall  f1-score   support
Iris-setosa       1.00      1.00      1.00        10
Iris-versicolor   0.95      0.90      0.92        10
Iris-virginica    0.92      0.95      0.93        10
