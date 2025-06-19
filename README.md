# 🫀 Heart Disease Predictor using Machine Learning

This project uses supervised machine learning algorithms to predict whether a person is likely to have heart disease, based on health-related features like blood pressure, cholesterol level, age, etc. The aim is to help in early detection and decision-making in medical settings.

---

## 🚀 Project Overview

Heart disease is a leading cause of death globally. In this project, we apply multiple ML algorithms on a publicly available dataset to classify patients as having heart disease (target = 1) or not (target = 0). We compare different models based on accuracy and visualize the results.

---

## 📊 Algorithms Used

We implemented and evaluated the following models:

- ✅ Logistic Regression
- ✅ Naive Bayes
- ✅ K-Nearest Neighbors (KNN)
- ✅ Decision Tree

Each model was trained on 70% of the data and tested on the remaining 30%.

---

## 🎯 Accuracy Scores

| Model               | Accuracy (%) |
|--------------------|--------------|
| Logistic Regression| 82.44        |
| Naive Bayes        | 87.80        |
| K-Nearest Neighbors| 70.73        |
| Decision Tree      | 97.07        |

> Decision Tree performed the best, but further evaluation (like cross-validation and overfitting checks) is recommended for real-world deployment.

---

## 📁 Dataset

- Source: [Heart Failure Prediction - Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- File: `heart.csv`
- Columns include:
  - `age`, `sex`, `chest pain type`, `cholesterol`, `thalach`, `restecg`, `fbs`, `exang`, `ca`, etc.
  - `target`: 1 = disease present, 0 = not present



