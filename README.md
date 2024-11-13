# Predicting H1N1 and Seasonal Flu Vaccinations

## Project Overview

This project aims to predict whether individuals received H1N1 and seasonal flu vaccines based on their background, opinions, and health behaviors. Using machine learning techniques, I analyze a dataset containing survey responses to forecast vaccination patterns.

## Dataset

The dataset used in this project is derived from the National 2009 H1N1 Flu Survey (NHFS). It includes information on:

- Demographic data (age, gender, etc.)
- Social factors  (household size, income, etc.)
- Health behaviors
- Opinions on vaccine effectiveness and risks

## Objectives

1. Develop predictive models for H1N1 and seasonal flu vaccine uptake
2. Identify key factors influencing vaccination decisions
3. Provide insights that could help improve vaccination rates

## Methodology

1. Data Preprocessing
- Clean and prepare the dataset, handling missing values and encoding categorical features.
2. Exploratory Data Analysis (EDA)
- Analyze distributions and relationships to uncover insights into vaccination trends and demographics.
3. Feature Engineering
- If posible create new features to improve model accuracy and capture interactions within the data.
4. Model Selection and Training
- Implement and tune models including: Logistic Regression, Random Forest, XGBoost, and a Neural Network.
5. Model Evaluation and Optimization
- Compare model performance using metrics like accuracy, F1 score, and AUC to select the best model.

## Technologies Used

- Python 3.10.5
- Pandas for data manipulation
- Scikit-learn for machine learning models
- Matplotlib and Seaborn for data visualization
- XGBoost for gradient boosting

## Project Structure

```
.
├── data
│   └── raw_data.csv           # Raw dataset (not included)
│   
├── Data_Analysis_Preprocessing_and_Model_Worflow.ipynb
│   ├── Exploratory Data Analysis
│   └── Model training and evaluation
│
├── README.md          
└── requirements.txt        
```