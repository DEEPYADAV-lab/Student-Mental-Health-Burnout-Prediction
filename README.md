# 🎓 Student Mental Health & Burnout Prediction using Machine Learning

## 📌 Project Overview

This project applies Machine Learning techniques to analyze student mental health data and predict burnout levels and mental health risk. The project includes data preprocessing, exploratory data analysis (EDA), visualization, regression, classification, and feature importance analysis using Python and Scikit-learn.

The objective is to identify students at risk of burnout and provide insights that could support early intervention strategies in educational institutions.

---

## 🚀 Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Linear Regression for Burnout Score Prediction
- Logistic Regression for Risk Level Classification
- Random Forest Classifier for Risk Prediction
- Feature Importance Analysis
- Model Performance Comparison

---

## 📂 Dataset

- Student Mental Health & Burnout Dataset
- Original dataset contains **1,000,000 student records**
- For faster model training, a **random sample of 100,000 records** was used.

### Dataset Features

- Age
- Gender
- Academic Year
- Study Hours per Day
- Exam Pressure
- Academic Performance
- Stress Level
- Anxiety Score
- Depression Score
- Sleep Hours
- Physical Activity
- Social Support
- Screen Time
- Internet Usage
- Financial Stress
- Family Expectation

### Target Variables

- Burnout Score (Regression)
- Risk Level (Low / Medium / High)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Machine Learning Models

### 1. Linear Regression
Predicts the student's burnout score.

**Performance**

- R² Score: **0.7078**
- RMSE: **0.9033**

---

### 2. Logistic Regression
Classifies students into Low, Medium, and High burnout risk.

**Performance**

- Accuracy: **29.85%**

---

### 3. Random Forest Classifier
Predicts student burnout risk using an ensemble learning approach.

**Performance**

- Accuracy: **70.69%**

---

## 📊 Top Important Features

According to the Random Forest model, the most influential features are:

1. Academic Performance
2. Social Support
3. Financial Stress
4. Exam Pressure
5. Sleep Hours
6. Family Expectation
7. Anxiety Score
8. Physical Activity

---

## 📈 Visualizations

The project includes:

- Burnout Score Distribution
- Risk Level Distribution
- Correlation Heatmap
- Actual vs Predicted Burnout Score
- Logistic Regression Confusion Matrix
- Random Forest Confusion Matrix
- Feature Importance Chart

---
 

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/DEEPYADAV-lab/Student-Mental-Health-Burnout-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

 

## 📌 Results

| Model | Task | Performance |
|------|------|------------|
| Linear Regression | Burnout Score Prediction | R² = **0.7078** |
| Logistic Regression | Risk Classification | Accuracy = **29.85%** |
| Random Forest | Risk Classification | Accuracy = **70.69%** |

---

## 🔮 Future Improvements

- Hyperparameter Tuning
- SMOTE for Class Imbalance
- XGBoost
- LightGBM
- Cross Validation
- Deep Learning Models
- Web-based Prediction System

---

## 👨‍💻 Author

**Deep Yadav**

B.Tech Computer Science Engineering

Machine Learning | Data Science | Python | SQL
