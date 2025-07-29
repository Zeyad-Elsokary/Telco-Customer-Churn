# Telco Customer Churn Prediction

This project aims to predict customer churn for a telecommunications company using supervised machine learning models. The primary goal is to identify customers who are likely to stop using the service, helping the business take proactive retention actions.

## Project Structure

- EDA & Preprocessing: Handling missing data, encoding categorical features, and feature scaling.
- Modeling: Trained multiple models including Logistic Regression, Random Forest, XGBoost, VotingClassifier, and StackingClassifier.
- Evaluation: Assessed model performance using Accuracy, Precision, Recall, F1 Score, and Classification Reports.
- Ensemble Models: Implemented ensemble methods to improve generalization.
- Interpretability: (Optional extension) Adding SHAP/LIME for explaining predictions.

## Dataset

- Source: IBM Sample Dataset
- Size: ~7,000 records
- Target Variable: `Churn` (Yes/No)

## Features Used

- Demographic information (e.g., gender, senior citizen)
- Service-related information (e.g., internet service, online security)
- Account information (e.g., contract type, monthly charges, total charges)
- Derived features (if any)

## Models Implemented

| Model                  | Description                        |
|------------------------|------------------------------------|
| Logistic Regression    | Baseline linear model              |
| Decision Tree          | Basic non-linear classifier        |
| Random Forest          | Bagging ensemble method            |
| XGBoost                | Boosting-based ensemble            |
| Voting Classifier      | Combines predictions (hard voting) |
| Stacking Classifier    | Meta-model on top of base models   |

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

*Note: Class imbalance was taken into consideration during evaluation.*

## Results Summary

- Best performing model: XGBoost / VotingClassifier (based on evaluation)
- Overall accuracy: ~XX%
- Model improvements using ensemble techniques

## Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn)
- XGBoost
- Matplotlib / Seaborn
- Jupyter Notebook


**Zeyad Elsokary**  
A passionate AI & Data Science practitioner focused on real-world problem solving.  
[LinkedIn Profile](https://www.linkedin.com/in/zeyad-elsokary/)
