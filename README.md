# Customer Churn Prediction Using Machine Learning

## Description
This repository contains the code, experiments, and documentation for the **Customer Churn Prediction** project. The goal of this project is to predict whether a customer is likely to churn based on demographic, financial, and behavioral attributes, enabling data-driven decision-making for customer retention.

## Project Overview
The objective of this project is to build and evaluate supervised machine learning models for predicting customer churn using structured banking data.

The project starts with exploratory data analysis (EDA) to understand customer behavior and identify key churn-driving factors. This is followed by data preprocessing, feature engineering, and model training. Multiple machine learning models are trained and compared to assess their effectiveness.

The analysis emphasizes both model performance and interpretability, highlighting how ensemble-based models can improve prediction accuracy over simpler decision-based approaches.


## Key Features

### Data Preprocessing
- Removal of irrelevant identifiers and duplicate records  
- Handling categorical variables using label encoding  
- Normalization of numerical features (Credit Score, Balance, Estimated Salary)  
- Train-test split to ensure unbiased evaluation  

### Exploratory Data Analysis (EDA)
- Analysis of churn distribution across:
  - Age  
  - Geography  
  - Gender  
  - Account Balance  
  - Tenure  
  - Number of Products  
  - Credit Card ownership  
  - Active membership status  
- Visualizations using Matplotlib and Seaborn  

### Machine Learning Models
- Implementation and evaluation of:
  - Decision Tree Classifier  
  - Random Forest Classifier  

### Hyperparameter Tuning
- Optimization using **GridSearchCV**
- Tuning of:
  - Max depth  
  - Minimum samples per leaf  
  - Splitting criteria (Gini, Entropy)  
  - Random state  

### Model Evaluation
- Performance evaluation using:
  - Accuracy  
  - Precision, Recall, and F1-score  
  - Confusion Matrix visualizations  
- Comparative analysis showing improved performance with Random Forest  


## Results & Insights
- Customer churn is strongly influenced by:
  - Age  
  - Geography  
  - Balance  
  - Number of products  
  - Credit card ownership  
  - Active membership status  
- The **Random Forest Classifier** achieved better accuracy and precision compared to the Decision Tree model, making it more suitable for churn prediction tasks.


## Tech Stack
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  
- **Model Optimization:** GridSearchCV  



