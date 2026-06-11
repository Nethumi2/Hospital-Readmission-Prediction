# Hospital-Readmission-Prediction

## Objective
Predict whether a diabetic patient will be readmitted within 30 days using machine learning.

## Dataset
UCI Diabetic Patient Dataset — 101,766 records, 50 features

## Tools & Technologies
Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Plotly

## Models Used
- Logistic Regression (ROC-AUC: 0.6374)
- Random Forest (ROC-AUC: 0.6502)
- Gradient Boosting (ROC-AUC: 0.6639) ✅ Best Model

## Key Findings
- Number of lab procedures is the strongest readmission predictor
- Clinically complex patients (more medications, longer stays) are highest risk
- Gradient Boosting achieved highest ROC-AUC of 0.6639
