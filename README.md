# HeartAttackPrediction

Cardiovascular diseases (CVDs) are the leading cause of death worldwide, making early prediction of heart attacks crucial for saving lives. This project leverages machine learning models to classify individuals as "at risk" or "not at risk" for a heart attack using clinical and demographic data.

Dataset Source: https://www.kaggle.com/datasets/thxogg/heart-attack-classification-training-dataset

Key Attributes: age, gender, heart rate (impulse), blood pressure (systolic & diastolic), blood glucose levels, creatine kinase-MB (KCM), troponin (heart muscle damage marker) Target Variable: class (heart attack: Yes/No)

Data preprocessing: Outliers were capped for heart rate, blood pressure, and glucose. Standardization and log transformation ensured consistency. Feature engineering included blood pressure ratio, heart rate categories (Low, Normal, High), and age groups (Young, Middle-aged, Elderly) for better interpretability.

Project Goals: This project aims to identify key clinical indicators of heart attack risk, develop and compare multiple machine learning models, and recommend the most effective model for accurate and early prediction. By leveraging data-driven insights, the goal is to enhance clinical decision-making and improve patient outcomes.

Models Implemented: Various machine learning models were explored, including Logistic Regression as a baseline, Support Vector Machine (SVM) for optimized classification, and ensemble methods like Random Forest, Gradient Boosting (GBM), XGBoost, and LightGBM to enhance predictive accuracy and robustness. Random Forest emerged as the top performer.

Key Findings: Random Forest outperformed all models with 98.2% accuracy and a 0.99 ROC-AUC, making it the most reliable choice. XGBoost and Gradient Boosting also showed strong results, while Logistic Regression and SVM had lower accuracy around 77–78%. LightGBM performed well but was less stable. Overall, ensemble models like Random Forest and XGBoost proved the most effective for heart attack prediction.
