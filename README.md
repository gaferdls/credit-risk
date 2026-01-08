# Credit Risk Prediction

This project builds a machine learning model to predict loan default using structured financial and demographic data.

## Dataset
- Loan default dataset from Kaggle
- Binary target: `Default` (1 = default, 0 = non-default)
- ~255k samples, mix of numerical and categorical features

## Approach
- Data preprocessing and feature engineering
- One-hot encoding for categorical variables
- Train-test split with stratification due to class imbalance
- Logistic Regression baseline model
- Evaluation using Accuracy and ROC-AUC

## Results
- Accuracy: ~88%
- ROC-AUC: ~0.75

## Tools
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

## Next Steps
- Random Forest and Gradient Boosting models
- Hyperparameter tuning
- Feature importance analysis