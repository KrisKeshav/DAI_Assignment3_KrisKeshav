# 🌸 Iris Dataset - Dimensionality Reduction & Model Evaluation

This project explores the effects of **dimensionality reduction** techniques on classification performance using the classic **Iris dataset**. It is structured as a hands-on tutorial notebook originally created in **Kaggle** and now available here for learning and reference.

---

## 📚 Overview

The notebook performs the following key steps:

1. **Data Loading & Preprocessing**
   - Load the Iris dataset (from Kaggle or `sklearn.datasets`)
   - Train/test split (70/30)
   - Standardize features using `StandardScaler`

2. **Baseline Model Training**
   - Train and evaluate four classifiers:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Support Vector Machine (SVM)
   - Evaluation metrics:
     - Accuracy, Precision, Recall, F1-Score
     - Confusion Matrix

3. **Dimensionality Reduction Techniques**
   - **PCA** (Principal Component Analysis) - Unsupervised
   - **LDA** (Linear Discriminant Analysis) - Supervised
   - Project data to 2D, retrain models, evaluate

4. **Performance Comparison**
   - Compare results across:
     - No Dimensionality Reduction
     - PCA
     - LDA
   - Visualize model F1-scores
   - Scatter plots for PCA and LDA-transformed data

---

## 📁 Files

- `Iris_Dimensionality_Reduction_Kaggle.ipynb`: Main notebook containing full analysis and visualizations.
- `README.md`: This file.

---

## 🛠 Tools & Libraries

- Python 3
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

---

## 📊 Results & Insights

- **LDA outperformed PCA** in most models due to its supervised nature that maximizes class separability.
- **PCA** slightly reduced performance in some cases as it preserves variance, not class distinctions.
- The **original full-featured models** achieved the best or close-to-best performance but at the cost of higher dimensionality.

---
