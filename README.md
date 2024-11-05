# StrokePredict-SVM

## Overview
This project explores and models the Stroke Prediction Dataset using Support Vector Machines (SVM) with different kernel functions. The analysis includes data preprocessing, exploratory data analysis (EDA), model training, and evaluation to predict stroke risk based on demographic, medical history, and lifestyle factors.

## Dataset
- **Size**: 5110 samples with 12 features
- **Features**: Demographic, medical, and lifestyle variables impacting stroke risk

## Project Workflow
1. **Data Exploration**: 
   - Examined distributions and relationships between variables with histograms, box plots, and descriptive statistics.
  
2. **Data Preprocessing**:
   - Imputed missing values for numerical features (mean) and categorical features (most frequent).
   - Standardized numerical features for improved model performance.

3. **Modeling**:
   - Trained SVM models using linear, polynomial, and RBF kernels.
   - Evaluated each model’s performance with classification metrics (accuracy, precision, recall, F1-score) and visualizations.

4. **Results**:
   - SVM models achieved high accuracy but struggled with stroke prediction (low precision and recall for positive class).
   - Kernel choice had minimal impact on model performance.

5. **Recommendations**:
   - Further tuning of hyperparameters and addressing class imbalance issues are recommended to enhance model performance.

## Conclusion
The SVM approach provided insights into stroke prediction with high accuracy, yet highlighted the need for refinement in identifying high-risk patients. Future work may involve exploring additional models and techniques to improve predictive power.

## Installation
- Clone the repository: `git clone https://github.com/yourusername/StrokePredict-SVM.git`
- Ensure required libraries are installed, including `numpy`, `pandas`, `sklearn`, and `matplotlib`.

---
