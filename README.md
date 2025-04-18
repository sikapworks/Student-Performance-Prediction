# Student-Performance-Prediction
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

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Running the Pipeline
1. **Clone the repository**
   ```bash
git clone https://github.com/yourusername/student-performance-prediction.git
cd student-performance-prediction
```
2. **Prepare the data**
   - Place `Student Performance Prediction.csv` in the `data/` directory.
3. **Execute**
   ```bash
python run_pipeline.py --data_path data/Student\ Performance\ Prediction.csv
```
4. **View Results**
   - Metrics printed to console  
   - Confusion matrix heatmap saved to `output/confusion_matrix.png`  
   - Feature importance plot saved to `output/feature_importance.png`

## File Structure
```
├── data/                         # Raw and processed datasets
│   └── Student Performance Prediction.csv
├── notebooks/                    # EDA and prototyping notebooks
│   └── exploratory_analysis.ipynb
├── src/                          # Source code modules
│   ├── preprocessing.py          # Data cleaning and encoding
│   ├── modeling.py               # Model training and evaluation
│   └── visualize.py              # Plotting utilities
├── output/                       # Generated figures and reports
├── run_pipeline.py              # Main entrypoint script
├── requirements.txt             # Python package dependencies
└── README.md                    # Project overview and instructions
```

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



