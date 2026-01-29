# Credit Card Fraud Detection using Random Forest

## Objective
To detect fraudulent credit card transactions using ensemble learning while handling imbalanced data.

## Dataset
Kaggle Credit Card Fraud Dataset  
- Total transactions: 284,807  
- Fraud cases: 492 (Highly imbalanced)

## Steps Performed
1. Loaded dataset and analyzed class imbalance
2. Removed non-useful columns (Time)
3. Applied stratified train-test split
4. Trained Logistic Regression as baseline model
5. Trained Random Forest with 100 trees
6. Evaluated models using Precision, Recall, F1-score
7. Visualized feature importance
8. Saved trained model using joblib

## Models Used
- Logistic Regression (Baseline)
- Random Forest Classifier

## Key Learnings
- Accuracy is misleading in imbalanced datasets
- Ensemble models perform better in fraud detection
- Feature importance helps understand fraud indicators

## Saved Files
- random_forest_fraud_model.pkl

## Tools
Python, Pandas, Scikit-learn, Matplotlib
