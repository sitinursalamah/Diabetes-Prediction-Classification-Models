# Diabetes Prediction: Comparison of Classification Models

This project focuses on comparing multiple classification models to predict the presence of diabetes based on clinical features. The goal is to identify the most effective model in terms of predictive performance using standard evaluation metrics.

## 🩺 Project Overview

- **Objective**: Predict whether a patient is diabetic using clinical data.
- **Dataset**:  Consisting of 768 samples and 9 features.

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📊 Workflow
1. **Data Preprocessing**:
   - Handling missing or zero values
   - Feature scaling and normalization
2. **Exploratory Data Analysis (EDA)**:
   - Feature correlation analysis
   - Visualization of key predictors
3. **Model Building**:
   - Logistic Regression
   - Decision Tree
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)
   - Random Forest
4. **Model Evaluation**:
   - Accuracy
   - ROC-AUC

## 🏆 Results

| Model               | Accuracy | ROC-AUC |
|--------------------|----------|---------|
| Logistic Regression| 86,84%   | 87%     |
| Decision Tree      | 90,13%   | 86%     |
| SVM                | 88,82%   | 88%    |
| KNN                | 87,5%    | 86%    |
| **Random Forest**  | **90.79%**| **89%** |

✅ **Random Forest** outperformed the other models and demonstrated robustness and reliability in predicting diabetes.
