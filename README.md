# Data-Driven Predictive Analysis for Brain Stroke Risk Assessment
This study aims to develop a machine learning model for early stroke prediction by integrating Publicly available dataset through Kaggle, ensuring accuracy, interpretability, and real-time applicability in healthcare settings.
Stroke Prediction using Machine Learning

Overview
This project focuses on predicting the likelihood of a person having a stroke using various machine learning algorithms. Accurate and early prediction can help in timely diagnosis and preventive healthcare.

Objective:
To build and compare different machine learning models to identify the most effective one for predicting stroke cases, especially minimizing false negatives.

Dataset:
    Source: Kaggle – https://www.kaggle.com/datasets/jillanisofttech/brain-stroke-dataset

    Features: age, gender, hypertension, heart disease, smoking status, BMI, average glucose level, etc.

    Target: Stroke (0 = No stroke, 1 = Stroke)

Technologies Used:

  Python,
  Jupyter Notebook,
  Pandas, NumPy, Matplotlib, Seaborn,
  Scikit-learn,
  XGBoost,
  Imbalanced-learn (SMOTE),
  Joblib (for model saving),

Methodology:

  Data Preprocessing,
  Handling missing values,
  Label encoding categorical variables,
  Feature scaling,
  Balancing data using SMOTE and Class weights,
  Model Training,
  Trained multiple models: Random Forest, Decision Tree, SVM, KNN, XGBoost,
  
  Used Class Weight adjustments and ensemble methods like Voting and Stacking,
  Model Evaluation,
  Evaluated using Accuracy, Precision, Recall, and F1-score
  Special focus on Recall and F1-score for stroke class (class 1).



Stacking Classifier performed best with:

  Accuracy: 96.48%,
  Precision (1): 0.96,
  Recall (1): 0.97,
  F1-score (1): 0.97

Results:

Achieved highest prediction accuracy with Stacking Classifier.
Model capable of identifying stroke patients with high precision and recall.

Future Work:

Deploy as a web application using Flask or Streamlit.
Integrate with real-time patient data from healthcare systems.

Author:
AC Janasivaguru

LinkedIn: www.linkedin.com/in/acjanasivaguru
