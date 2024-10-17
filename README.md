# Predicting heart disease risk Project
## Table of Contents
 - [Project Overview](#project-overview)
 - [Data preprocessing](#data-preprocessing)
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Feature Selection](#feature-selection)
 - [Model Selection](#model-selection)
 - [Model Validation and Training](#model-validation-and-training)
 - [Findings](#findings)        
 - [Recommendation](#recommendation)

This Python project focuses on analyzing a healthcare dataset from Massachusetts General Hospital through a structured approach that includes data preprocessing, exploratory data analysis (EDA), feature selection, model selection, and model validation.

Data Preprocessing: The project begins with importing necessary libraries (NumPy and Pandas) and loading the dataset from a CSV file into Jupyter Notebook. Initial data inspection revealed the presence of null values, which were addressed by replacing categorical variables with the mode and continuous variables with the mean. Duplicate entries were also removed to ensure data integrity.

Exploratory Data Analysis (EDA): Basic statistics of the dataset were captured, providing insights into data distribution and characteristics.

Feature Selection: The relevant features for model training were identified, with TenYearCHD designated as the target variable (denoted as 'y'). The first five rows of this target feature were reviewed to confirm accurate selection.

Model Selection: Given the diversity of potential models, five different machine learning algorithms were tested to determine the most effective for the dataset. These models included Decision Tree Classifier, Logistic Regression, K-Nearest Neighbor (KNN), Support Vector Machine (SVM), and Random Forest.

Model Validation and Training: The dataset was split into training and testing subsets in an 80:20 ratio. Each model was trained and validated, yielding the following accuracies:

Decision Tree Classifier: 79.12%
Logistic Regression: 85.73%
K-Nearest Neighbor (KNN): 84.2%
Support Vector Machine (SVM): 85.49%
Random Forest: 85%
Based on these results, the Logistic Regression model emerged as the most suitable option for predicting outcomes in the Massachusetts General Hospital dataset, demonstrating the highest accuracy among the tested models.



