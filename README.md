# Student Performance Prediction

## Overview
A machine learning pipeline for predicting whether a student will pass or fail a semester based on demographic, academic, and behavioral data. Early identification of at-risk students enables targeted interventions to improve success rates.

## Features
- **Data Preprocessing**: Label encoding of categorical features, noise feature injection to test model robustness.
- **Modeling**: Random Forest Classifier with configurable hyperparameters.
- **Evaluation**: Accuracy, Precision, Recall metrics, and confusion matrix interpretation.
- **Visualization**: Plots for data distributions, correlations, and performance diagnostics.

## Quick Start
### Prerequisites
- Python 3.8+  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn

## Methodology
1. **Exploratory Data Analysis**: Examine distributions, correlations, and class balance.  
2. **Preprocessing**: Encode categorical variables, create binary target, inject noise.  
3. **Model Training**: Train Random Forest with `n_estimators=10`, `max_depth=5`.  
4. **Evaluation**: Compute accuracy, precision, recall; generate confusion matrix.

## Results
| Metric    | Value |
|-----------|-------|
| Accuracy  | 0.85  |
| Precision | 0.88  |
| Recall    | 0.92  |

*Refer to `output/` for detailed visualizations and report.*

## Future Work
- Hyperparameter tuning with grid search  
- Incorporate advanced models (e.g., Gradient Boosting)  
- Address class imbalance with SMOTE or class weights  
- Feature engineering (interaction terms, temporal trends)

## License
MIT License


![Screenshot 2025-04-18 153348](https://github.com/user-attachments/assets/20110dde-87a3-4af2-a54b-c05bda0a8f19)

![Screenshot 2025-04-18 155218](https://github.com/user-attachments/assets/b8075fb2-19ea-4194-8bfe-d9a5feed86d4)
