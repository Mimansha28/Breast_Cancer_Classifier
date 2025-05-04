# Breast_Cancer_Classifier

This project is a **Breast Cancer Classification System** that uses **machine learning algorithms** to predict whether a tumor is **benign** or **malignant** based on various features extracted from cell nuclei present in breast mass.

## Objective

To develop a system that accurately classifies breast cancer tumors using machine learning, helping in the **early detection and diagnosis** of breast cancer.

## Features

- Predicts if a tumor is **benign** or **malignant**
- Evaluates multiple machine learning models
- Visualizes key data insights and model performance
- Supports early diagnosis through automated classification

## 🗃 Dataset

The system uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**, which includes 30 real-valued features computed from digitized images of fine needle aspirate (FNA) of breast mass.

- Features include: 
  - Radius, Texture, Perimeter, Area, Smoothness, etc. (mean, standard error, and worst cases)
- Target variable:
  - `M` = Malignant
  - `B` = Benign

Dataset Source: [UCI ML Repository – Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

## Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

## ML Algorithms Implemented

- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest Classifier
- Naive Byes Classifier

## 🧠 Best Performing Model

The **Random Forest** classifier demonstrated the highest accuracy and overall performance, making it the final model choice for this system.
