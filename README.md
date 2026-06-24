# Healthcare Insurance Cost Prediction: An XAI Approach

## Project Overview
This project leverages Machine Learning and Explainable AI (XAI) techniques to predict healthcare insurance charges and provide transparent, interpretable insights into the factors driving costs. Using the Healthcare Insurance Dataset from Kaggle, we built a Random Forest Regressor that achieves 86.43% R² on test data while maintaining interpretability through SHAP and LIME explanations.

Key Highlights
- Model Performance: R² of 97.43% (training) and 86.43% (testing), demonstrating robust predictive power with controlled overfitting.

- Explainability: Implemented SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations) to demystify model predictions.

- Business Impact: Identified that smoking status, BMI, and age are the strongest predictors, with smoking having a multiplicative effect on charges.

- Interactive Dashboard: Tableau Public dashboard for real-time exploration of insurance cost drivers.

Technologies Used
Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

XAI Libraries: SHAP, LIME

Modeling: Random Forest Regressor, MLP Neural Network (for comparison)

Visualization: Tableau Public

Version Control: Git & GitHub
