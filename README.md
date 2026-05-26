# ML_Project_Heart_Stroke_Prediction
Machine learning-based stroke prediction system using healthcare data with EDA, preprocessing, SMOTE, feature selection, hyperparameter tuning, and classification models for improved stroke risk detection.


# Stroke Prediction Using Machine Learning

This project focuses on predicting stroke occurrence using healthcare data through machine learning techniques. The project includes exploratory data analysis (EDA), data preprocessing, handling missing values, encoding categorical features, model training, imbalance handling using SMOTE, feature selection, hyperparameter tuning, and performance evaluation.

Several classification models including Logistic Regression, Support Vector Machine (SVM), Decision Tree, Random Forest, and XGBoost were compared. Due to class imbalance, baseline models showed high accuracy but poor recall. Applying SMOTE significantly improved the Decision Tree model, resulting in better detection of stroke cases.

## Features
- Exploratory Data Analysis (EDA)
- Missing value handling
- One-hot encoding for categorical variables
- Multiple ML model comparison
- SMOTE for imbalanced data handling
- Feature selection using SelectKBest (f_classif)
- Hyperparameter tuning using GridSearchCV
- Confusion matrix and evaluation metrics
- Final optimized Decision Tree model

## Best Model Performance
- Accuracy: ~92%
- Precision: ~91%
- Recall: ~94%
- F1 Score: ~92%

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Decision Trees
- Imbalanced-learn (SMOTE)
