# exploring_mental_health_data
This repository contains an analysis of the Mental Health Data from a Kaggle competition. The project focuses on exploring factors associated with mental health issues and building predictive models to understand the prevalence of mental health conditions.

Table of Contents: 
Project Overview
Dataset
Objective
Data Preprocessing
Exploratory Data Analysis (EDA)
Modeling
Results
Usage
Contributing
License

Project Overview
Mental health is a significant aspect of public health, and this competition provides data to help understand various factors influencing mental health conditions. This project examines patterns and uses predictive modeling to identify individuals who may be at risk of mental health issues.

Dataset
The dataset used for this project is provided by Kaggle. It includes features such as demographic information, personal habits, work or academic pressures, family history, and more. The target variable is a label indicating whether the individual experiences symptoms of depression.

Key columns:
Age
Gender
Work/Study Hours
Financial Stress
Family History of Mental Illness
Depression (target variable)


Data Preprocessing:
Handled missing values using imputation techniques tailored to different columns.
Converted categorical variables to numerical values using OneHotEncoding and OrdinalEncoding where appropriate.
Applied scaling to ensure that the features are on a similar scale for modeling.



Machine learning algorithms applied:

Logistic Regression: Baseline model.
Random Forest Classifier: For feature importance and better accuracy.
XGBoost Classifier: Optimized using hyperparameter tuning for enhanced performance.
Isolation Forest was used to handle outliers, ensuring a clean dataset for modeling.

Results
Evaluation metrics:
Accuracy: Achieved an accuracy score of XX%.
Precision, Recall, F1 Score: These metrics were also calculated to provide a holistic view of the model’s performance.
The results indicate that certain features, such as financial stress and family history of mental illness, are highly predictive of mental health issues.

