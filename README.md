# Sentiment Analysis on Gamesphere Reviews

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![NLTK](https://img.shields.io/badge/NLTK-✔-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-✔-blue)

## Overview
This project performs sentiment analysis on text data to classify opinions as **positive, or negative**.

## Tools Used
- **Python**
- **NLTK**
- **Scikit-Learn**
- **Pandas**
- **Matplotlib**
- **Seaborn**

## Machine Learning Models Used
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **XGBoost Classifier**
- **Gradient Descent**
- **GridSearchCV for Hyperparameter Tuning**

## Approach
1. **Data Loading & Cleaning:**  
   - Loaded customer data from CSV files.  
   - Identified and handled missing values in the dataset.  
   - Converted categorical variables to numerical values using encoding techniques.

2. **Exploratory Data Analysis (EDA):**  
   - Visualized data distributions and correlations between features.
   - Generated wordclouds to visualize user review text data 

3. **Model Training:**
   - Used **TF-IDF** for traditional ML models.
   - Implemented **Logistic Regression, KNN, Random Forest, Gradient Descent, XGBoost** for baseline models.  

5. **Evaluation & Performance Metrics:**  
   - Compared different models using **accuracy, precision, recall, and F1-score**.  
   - Visualized results using confusion matrices and sentiment distributions.  

## Results
- Achieved **84% accuracy** using fine-tuned Machine Learning models.
