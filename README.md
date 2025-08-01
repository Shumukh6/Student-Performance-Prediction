# 🎓 Student Performance Prediction

A Machine Learning project to predict students' performance using regression and classification models.

---

## 📊 Project Overview

This project analyzes students' academic performance using various features such as gender, lunch type, and test preparation course.
We built two machine learning models:

- **Linear Regression** to predict writing scores.
- **Logistic Regression** to classify students as Pass/Fail.

---

## 🧠 Models Used

### 1. Linear Regression
- **Input Features:** Math score, Reading score
- **Target Variable:** Writing score
- **Objective:** Learn the best-fit line to minimize prediction error (MSE)

### 2. Logistic Regression
- **Input Features:** Math score, Reading score, Gender, Lunch, Test Preparation
- **Target Variable:** Pass/Fail (based on average score >= 60)
- **Objective:** Classify student performance into Pass or Fail

---

## 🗃️ Dataset

The dataset contains scores and demographic data for students, with the following columns:
- `math score`
- `reading score`
- `writing score`
- `gender`
- `lunch`
- `test preparation course`

---

## 📈 Results

### Linear Regression
- High correlation between math, reading, and writing scores.
- Model evaluated using **Mean Squared Error**.

### Logistic Regression
- **Accuracy:** 98%
- **Precision/Recall/F1-score:** High scores on both classes (Pass & Fail)
- **Evaluation:** Confusion Matrix & Classification Report

---

## 📌 Project Files

- `Student_Performance_Prediction.ipynb` – Jupyter notebook containing all analysis, visualizations, and model training.
- `README.md` – Project overview and description.

---

## 📅 Last Updated
August 01, 2025

---

## 🧑‍💻 Author
Shumukh6  
GitHub: [@Shumukh6](https://github.com/Shumukh6)
