# 🦠 Machine Learning–Based Diagnosis of COVID-19 from Clinical and Laboratory Data

## 📌 Project Overview
This project focuses on the diagnosis of COVID-19 using real-world clinical and laboratory data collected from hospital patients.  
The objective is to assist clinical decision-making by identifying the most relevant biomarkers and building reliable machine learning models, despite noisy and highly incomplete medical data.

The dataset comes from Kaggle and contains demographic information, viral test results, and blood test measurements.

---

## 🎯 Objectives
- Perform a **professional exploratory data analysis (EDA)** on medical data.
- Handle **high missingness** and noisy clinical variables.
- Identify **discriminative biomarkers** associated with COVID-19.
- Build and evaluate **machine learning models** with a focus on recall.
- Apply **statistical hypothesis testing** to validate medical assumptions.
- Interpret model behavior using **Explainable AI techniques**.

---

## 📊 Exploratory Data Analysis (EDA)
- Target variable analysis and class imbalance study.
- Missing value visualization and analysis.
- Distribution analysis of biological variables.
- Correlation analysis between blood tests, viral tests, and age.
- Outlier detection using the IQR method.
- Hypothesis formulation based on clinical intuition.

---

## 🧹 Data Preprocessing
- Selection of relevant variables based on missing rate thresholds.
- Encoding of categorical medical results.
- Feature engineering (e.g. viral infection indicator).
- Handling missing values through row-wise filtering.
- Train-test split with class distribution control.

---

## 🧪 Statistical Tests
- Chi-square test for categorical variables.
- Mann–Whitney U test for non-parametric comparison of blood markers.
- Validation of null hypotheses related to COVID-19 biomarkers.

---

## 🤖 Machine Learning Models
Models evaluated include:
- Random Forest Classifier
- Feature-enhanced Random Forest (Polynomial Features + SelectKBest)

Evaluation metrics:
- Confusion matrix
- Precision, Recall, F1-score
- Learning curves
- Cross-validation

A strong emphasis is placed on **recall**, due to the medical context.

---

## 🔍 Model Interpretability (XAI)
- Feature importance analysis
- Permutation-based reasoning
- Medical interpretation of influential biomarkers

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---
