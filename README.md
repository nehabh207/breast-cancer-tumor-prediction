# breast-cancer-tumor-prediction
Random Forest classification of breast tumors (malignant vs benign) on the Wisconsin Diagnostic dataset, with exploratory plots and feature importance analysis.
# Breast Cancer Classification (Machine Learning)

Classifying breast tumors as malignant or benign using the Wisconsin Diagnostic Breast Cancer dataset.

## Goal
Predict whether a tumor is malignant or benign from cell-nucleus measurements, and find which features matter most.

## Data
Wisconsin Diagnostic Breast Cancer dataset (569 samples, 30 features), loaded from scikit-learn.

## Methods
- Exploratory plot of tumor size by group
- Random Forest classifier (80/20 train-test split)
- Confusion matrix, precision, recall, F1
- 5-fold cross-validation
- Comparison with Logistic Regression and SVM
- Feature importance analysis

## Results
- Random Forest test accuracy: 95.6%, malignant recall: 0.93
- Cross-validated accuracy: Logistic Regression 98.1%, SVM 97.4%, Random Forest 95.6%
- The simpler Logistic Regression performed best in this dataset.

## Limitations
- Small dataset from a single source
- Uses pre-extracted measurements, not images
- Not clinically validated; for learning and research demonstration only

## Tools
Python, pandas, scikit-learn, matplotlib, seaborn, Google Colab

## Note on AI use
AI tools were used for code assistance and drafting. All analysis, results, and interpretation were reviewed and verified by me.

## Files
- `breast_cancer_classification.ipynb` – full analysis notebook
