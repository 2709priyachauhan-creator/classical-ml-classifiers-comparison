**Project Overview**
This project presents a comprehensive comparative analysis of 11 classical machine learning algorithms to predict high-risk medical conditions. The primary objective is to build, evaluate, and compare these models focusing on their performance, generalization, bias-variance tradeoffs, and the specific effects of L1 and L2 regularization. Given the critical nature of healthcare analytics, the evaluation heavily prioritizes Recall alongside overall accuracy to minimize life-threatening false negatives.
**Dataset**
 * Source: Breast Cancer Wisconsin Dataset (via scikit-learn)
 * Size: 569 samples
 * Features: 30 continuous numerical features
 * Target: Binary classification (Malignant / Benign)
**Models Implemented**
The following classical algorithms and ensemble methods were trained and evaluated:
 * K-Nearest Neighbors (KNN)
 * Logistic Regression (Standard, L1 Lasso, and L2 Ridge Regularization)
 * Linear Regression (Adapted with a binary threshold for comparison)
 * Decision Tree
 * Bagging Classifier (Decision Tree base)
 * Random Forest
 * Support Vector Machines (Linear and RBF kernels)
 * Linear Discriminant Analysis (LDA)
 * Naive Bayes (Gaussian)
 * **Evaluation Metrics**
Model performance was tracked using a standardized evaluation pipeline capturing:
 * Accuracy: Overall correctness of predictions.
 * Precision: Accuracy of positive high-risk predictions.
 * Recall: The model's ability to successfully identify all actual high-risk patients (Critical Metric).
 * F1-Score: The harmonic mean of Precision and Recall.
 * Confusion Matrix: Breakdown of True/False Positives and Negatives.
**Tech Stack**
 * Language: Python
 * Libraries: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
 * Environment: Jupyter Notebook / Google Colab
