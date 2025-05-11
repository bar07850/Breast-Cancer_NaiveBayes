# Breast Cancer Classification with Naive Bayes

This notebook demonstrates a simple approach to classifying breast cancer tumors as malignant or benign using the UCI Breast Cancer Wisconsin dataset and the Gaussian Naive Bayes algorithm.

## 📋 Project Overview

The goal of this project is to:
- Load and preprocess the breast cancer dataset
- Train a Naive Bayes classifier to predict tumor type
- Evaluate the model’s performance on test data

This is a beginner-friendly example for understanding basic supervised learning.

## 📦 Dataset

- **Dataset:** Breast Cancer Wisconsin Diagnostic Dataset
- **Source:** Built-in from `sklearn.datasets`
- **Features:** 30 numeric attributes related to tumor characteristics
- **Target:** Binary classification (0 = malignant, 1 = benign)

## 🛠️ Methodology

### Data Preprocessing
- Dataset is split into training (80%) and test (20%) sets using `train_test_split`.

### Model
- A **Gaussian Naive Bayes classifier** was trained using `sklearn.naive_bayes.GaussianNB()`.

### Evaluation
- Model accuracy was measured on the test set.
- A full classification report (precision, recall, f1-score) was generated.

## 💻 How to Run

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/breast-cancer-naive-bayes.git
cd breast-cancer-naive-bayes

