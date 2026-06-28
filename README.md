# ❤️ Heart Disease Prediction using Machine Learning

A Machine Learning project that predicts the likelihood of heart disease using patient health records. The project applies data preprocessing, feature engineering, and multiple classification algorithms through a Scikit-learn Pipeline to build and evaluate predictive models.

---

## 📖 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can assist healthcare professionals in providing timely diagnosis and treatment.

This project uses machine learning techniques to classify whether a patient is likely to have heart disease based on clinical attributes such as age, cholesterol, blood pressure, chest pain type, and other medical parameters.

---

## 🚀 Features

* Data Cleaning and Preprocessing
* Missing Value Handling
* Feature Scaling
* One-Hot Encoding for Categorical Features
* Scikit-learn Pipeline Implementation
* ColumnTransformer for Feature Engineering
* Multiple Machine Learning Models
* Model Performance Evaluation
* Heart Disease Prediction

---

## 🛠️ Technologies Used

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Programming Language      |
| Pandas           | Data Manipulation         |
| NumPy            | Numerical Computation     |
| Matplotlib       | Data Visualization        |
| Seaborn          | Statistical Visualization |
| Scikit-learn     | Machine Learning          |
| Jupyter Notebook | Development Environment   |

---

## 📊 Dataset

The project uses the **Heart Disease Dataset** from Kaggle.

**Dataset Link**

https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

### Dataset Features

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression (Oldpeak)
* Slope
* Number of Major Vessels (CA)
* Thalassemia
* Target (Heart Disease)

---

## 🔄 Machine Learning Pipeline

```text
Heart Disease Dataset
        │
        ▼
Data Preprocessing
        │
        ├── Missing Value Imputation
        ├── Feature Scaling
        ├── One-Hot Encoding
        │
        ▼
Column Transformer
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
        │
        ├── Logistic Regression
        ├── Random Forest
        ├── Support Vector Machine (SVM)
        └── K-Nearest Neighbors (KNN)
        │
        ▼
Model Evaluation
        │
        ▼
Heart Disease Prediction
```

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented and evaluated:

* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

---

## 📈 Model Evaluation

The models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

## 📚 Python Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* kagglehub

---

## 🎯 Future Enhancements

* Hyperparameter Tuning
* XGBoost and LightGBM Models
* Deep Learning Model
* Flask/Streamlit Web Application
* Model Deployment on Cloud
* Explainable AI using SHAP/LIME


---

## 📄 License

This project is intended for educational and learning purposes.
