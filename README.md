# diabetes-prediction
Predicting diabetes risk using LR, SVM, KNN, and Random Forest
# 🩺 Diabetes Prediction Using Machine Learning

This project aims to predict whether a patient is likely to have diabetes based on medical diagnostic measurements. Multiple classification models were applied and compared for performance.

---

## 📊 Dataset Overview
- **Source**: Kaggle – Pima Indians Diabetes Dataset
- **Rows**: 768 patients
- **Columns**: 8 medical input features + `Outcome` (target)
  - `Pregnancies`, `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`, `DiabetesPedigreeFunction`, `Age`

---

## 🔍 Exploratory Data Analysis (EDA)
- Distribution plots of Glucose, Age, BMI, etc.
- Correlation heatmap to identify key features
- Class imbalance check (`Outcome`: 0 vs. 1)
- Checked for zero-values in medical fields

---

## 🧼 Data Preprocessing
- Replaced 0s in `Glucose`, `BloodPressure`, `BMI`, etc. with medians
- Standardized features using `StandardScaler`
- Split into 80/20 train-test sets

---

## 🧠 Models Trained
| Model                  | Description                        |
|------------------------|------------------------------------|
| ✅ Logistic Regression | Baseline binary classifier         |
| ✅ SVM                 | Good for high-dimensional data     |
| ✅ K-Nearest Neighbors | Distance-based learner              |
| ✅ Random Forest       | Ensemble tree model                |

---

## 📈 Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## ✅ Results Summary
| Model             | Accuracy |
|------------------|----------|
| Logistic Regression | ~77%  |
| SVM                 | ~78%  |
| KNN (k=5)           | ~74%  |
| Random Forest       | ~81% ✅ |

> **Random Forest** achieved the best performance, followed by SVM.

---

## 🧪 Skills Demonstrated
- Applied multiple classification algorithms
- Performed feature scaling and data cleaning
- Evaluated models using key metrics
- Visualized class performance with heatmaps

---

## 📎 Related Links
- 📘 [Kaggle Notebook](https://www.kaggle.com/code/mahmoudehab6677/diabetes-prediction-lr-svm-knn-rf)

---
