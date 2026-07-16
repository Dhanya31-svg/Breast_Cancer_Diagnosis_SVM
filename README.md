# 🩺 Breast Cancer Diagnosis using Support Vector Machine (SVM)

## 📌 Overview

This project demonstrates an end-to-end Machine Learning workflow using the **Support Vector Machine (SVM)** algorithm to classify breast tumors as **Benign** or **Malignant** based on medical features. The notebook covers the complete ML pipeline, including data generation, preprocessing, feature scaling, model training, evaluation, hyperparameter tuning, and prediction.

---

## 🎯 Problem Statement

Early detection of breast cancer plays a vital role in improving treatment outcomes. This project builds an SVM classifier that predicts whether a breast tumor is **Benign (Non-Cancerous)** or **Malignant (Cancerous)** using patient measurements.

**Target Variable**

- **0 → Benign**
- **1 → Malignant**

---

## 📊 Dataset

A realistic synthetic medical dataset was created for this project.

### Features

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness

**Target**

- Diagnosis (Benign / Malignant)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 🎓 SVM Concepts Covered

- Support Vector Machine (SVM)
- Hyperplane
- Support Vectors
- Maximum Margin
- Hard Margin vs Soft Margin
- Kernel Trick
- Linear Kernel
- Polynomial Kernel
- RBF (Gaussian) Kernel
- Feature Scaling using StandardScaler
- Hyperparameter Tuning
- Model Evaluation

---

## 📈 Machine Learning Workflow

- Synthetic Dataset Creation
- Exploratory Data Analysis (EDA)
- Missing Value Handling
- Duplicate Removal
- Feature Scaling
- Train-Test Split
- SVM Model Training
- Kernel Comparison
- Model Evaluation
- Hyperparameter Tuning using GridSearchCV
- Model Saving & Loading
- Prediction on New Patient Data

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score
- Classification Report

---

## 📁 Project Structure

```
Breast_Cancer_Diagnosis_SVM.ipynb
BreastCancerSVM.pkl
StandardScaler.pkl
README.md
```

---

## 🚀 Key Highlights

- Built a complete Support Vector Machine classification model.
- Generated a realistic synthetic breast cancer dataset.
- Applied feature scaling using StandardScaler.
- Explored Linear, Polynomial, and RBF kernels.
- Evaluated model performance using multiple classification metrics.
- Tuned hyperparameters using GridSearchCV.
- Saved and loaded the trained model using Joblib.
- Predicted the diagnosis for new patient data.

---

## 📌 Future Improvements

- Train the model using real-world medical datasets.
- Deploy the model with Streamlit or Flask.
- Integrate patient data input through a web application.
- Compare SVM with Logistic Regression, Decision Tree, Random Forest, and XGBoost.
- Add model explainability using SHAP or LIME.

---

## 🎯 Learning Outcomes

By completing this project, you will understand:

- How Support Vector Machine works.
- Why feature scaling is essential for SVM.
- The concept of hyperplanes and support vectors.
- The importance of maximizing the margin.
- The purpose of different kernel functions.
- The effects of the C and Gamma parameters.
- How to evaluate a classification model.
- How to build a complete end-to-end SVM pipeline.

---

## 👨‍💻 Author

**Dhanya Sri**

Aspiring AI/ML Engineer | Data Science Enthusiast

---

## ⭐ If you found this project helpful, consider giving it a star!
