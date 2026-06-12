# Titanic-Survival-Prediction-Model

A machine learning project that predicts whether a passenger survived the Titanic disaster based on passenger information such as age, gender, class, fare, and other features.

## Overview

This project explores different machine learning algorithms for binary classification. Multiple models were trained and compared to find the best-performing approach. After evaluation, **Logistic Regression** was selected as the final model because it provided better generalization, while other models showed signs of overfitting or lower accuracy.

## Features

- Data cleaning and preprocessing  
- Handling missing values  
- Feature engineering  
- Exploratory Data Analysis (EDA)  
- Model training and comparison  
- Survival prediction

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Models Implemented

- Logistic Regression ✅ (Final Model)
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

## Workflow

1. Load Titanic dataset  
2. Perform data analysis and preprocessing  
3. Create useful features  
4. Train multiple ML models  
5. Compare model performance  
6. Select the best generalized model  
7. Predict passenger survival

## Model Selection

Although complex models like Decision Tree and Random Forest performed well on training data, they suffered from overfitting. Some models also produced lower validation accuracy.

**Logistic Regression** was chosen as the final model due to:
- Better balance between training and validation performance  
- Lower overfitting  
- Simple and interpretable approach  

## Goal

The goal of this project is to apply machine learning techniques to a real-world classification problem and understand model evaluation, comparison, and selection.

## Future Improvements

- Hyperparameter tuning  
- Advanced feature engineering  
- Ensemble techniques  
- Deploy model using Flask/Streamlit  

---
Built with Python & Machine Learning 🚀
