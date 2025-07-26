[![Python](https://img.shields.io/badge/project-blue)
# Iris Logistic Regression

A clean, modular pipeline to classify Iris flower species using Logistic Regression. All development and model training happens on Kaggle; results and artifacts are then published here.

```
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
```

## 🎨 Results
Sepal Length Distribution
```
Sample Classification Report
Accuracy: 1.00
               precision    recall  f1-score   support
Iris-setosa       1.00      1.00      1.00        10
Iris-versicolor   1.00      1.00      1.00        9
Iris-virginica    1.00      1.00      1.00        11
```
