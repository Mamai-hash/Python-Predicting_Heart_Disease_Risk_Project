## Predicting heart disease risk Project
### Table of Contents
 - [Project Overview](#project-overview)
 - [Data preprocessing](#data-preprocessing)
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Feature Selection](#feature-selection)
 - [Model Selection](#model-selection)
 - [Model Validation and Training](#model-validation-and-training)
 - [Findings](#findings)        

#### Project Overview
This Python project focuses on analyzing a healthcare dataset from Massachusetts General Hospital through a structured approach that includes data preprocessing, exploratory data analysis (EDA), feature selection, model selection, and model validation.

#### Data Preprocessing 
The project begins with importing necessary libraries (NumPy and Pandas) and loading the dataset from a CSV file into Jupyter Notebook. Initial data inspection revealed the presence of null values, which were addressed by replacing categorical variables with the mode and continuous variables with the mean. Duplicate entries were also removed to ensure data integrity.

![WhatsApp Image 2024-10-17 at 22 12 44](https://github.com/user-attachments/assets/92691f25-01ee-4c8f-8258-5d157d8bea16)

![WhatsApp Image 2024-10-17 at 22 14 14](https://github.com/user-attachments/assets/1aa77b7a-2d03-4b78-a864-2f460da96b2b)

#### Exploratory Data Analysis (EDA) 
Basic statistics of the dataset were captured, providing insights into data distribution and characteristics.
![WhatsApp Image 2024-10-17 at 22 19 12](https://github.com/user-attachments/assets/36e4786d-5ec7-49d9-9078-40d955c9b7b4)

#### Feature Selection 
The relevant features for model training were identified, with TenYearCHD designated as the target variable (denoted as 'y'). The first five rows of this target feature were reviewed to confirm accurate selection.
![WhatsApp Image 2024-10-17 at 22 15 47](https://github.com/user-attachments/assets/12806325-5737-4d27-b2f8-f5d7f02fbdfc)

#### Model Selection 
Given the diversity of potential models, five different machine learning algorithms were tested to determine the most effective for the dataset. These models included Decision Tree Classifier, Logistic Regression, K-Nearest Neighbor (KNN), Support Vector Machine (SVM), and Random Forest.
![WhatsApp Image 2024-10-17 at 22 16 11](https://github.com/user-attachments/assets/42c7f555-e986-44bf-8a98-dd5cbe3439d2)

#### Model Validation and Training 
The dataset was split into training and testing subsets in an 80:20 ratio. Each model was trained and validated, yielding the following accuracies:

1. Decision Tree Classifier: 79.12%
2. Logistic Regression: 85.73%
3. K-Nearest Neighbor (KNN): 84.2%
4. Support Vector Machine (SVM): 85.49%
5. Random Forest: 85%
![WhatsApp Image 2024-10-17 at 22 17 44](https://github.com/user-attachments/assets/7dfa6357-fce2-49e2-9e31-baf5a69dfc09)

#### Findings
Based on these results, the Logistic Regression model emerged as the most suitable option for predicting outcomes in the Massachusetts General Hospital dataset, demonstrating the highest accuracy among the tested models.



