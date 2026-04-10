# Titanic-Mini-Project-Code
This project analyzes the Titanic dataset and builds survival prediction models using Random Forest, Extreme Learning Machine (ELM), and a custom RVFL network. It includes data cleaning, EDA, visualization, and model comparison using accuracy and F1-score. Created for learning end-to-end classification workflows.

# Titanic Survival Prediction Mini Project

This project analyzes the Titanic dataset and builds machine learning models to predict passenger survival. It covers the full workflow from data cleaning and exploratory data analysis (EDA) to model training, evaluation, and comparison.

## Purpose
This notebook was created to practice an end-to-end classification project using a well-known real-world dataset. The goal is to understand how passenger features such as sex, class, age, fare, and embarkation point relate to survival, and to compare multiple models on the same task.

## What the project does
- Loads the Titanic dataset
- Cleans missing values
- Performs descriptive statistics and exploratory data analysis
- Visualizes survival patterns across different features
- Preprocesses categorical and numerical variables
- Trains multiple classification models
- Evaluates model performance using accuracy and F1-score
- Compares results with summary tables and plots

## Features Used
The project uses the following input features:
- **Pclass**
- **Sex**
- **Age**
- **Fare**
- **Embarked**

Target variable:
- **Survived**

## Exploratory Data Analysis
The notebook includes analysis such as:
- average passenger age
- survival rate by gender
- survival rate by passenger class
- relationship between fare and survival
- age distribution of survivors vs non-survivors

These visualizations help identify important patterns before training models.

## Models Compared

### 1. Random Forest
A tree-based ensemble model used as a strong baseline for classification.

### 2. Extreme Learning Machine (ELM)
A lightweight neural-style model with random hidden layer weights and a trainable output layer.

### 3. Custom RVFL
A custom Random Vector Functional Link model that combines transformed hidden features with direct input connections.

## Evaluation Metrics
The models are compared using:
- **Accuracy**
- **F1-score**

These metrics help measure both overall prediction quality and classification balance.

## Why this project is useful
This project is useful for:
- learning the complete machine learning workflow
- practicing data cleaning and feature preprocessing
- understanding EDA in classification problems
- comparing traditional and neural-inspired models
- building a strong beginner-friendly portfolio project

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
- Titanic dataset

## Outputs
The notebook generates:
- cleaned and processed data
- descriptive statistics
- EDA visualizations
- model performance metrics
- comparison plots for all models

## Key Learning Outcome
This project shows that feature analysis and preprocessing are important steps before modeling, and that different classifiers can be compared effectively using the same dataset and evaluation metrics.

## Future Improvements
Possible extensions include:
- adding Logistic Regression, SVM, or XGBoost
- performing hyperparameter tuning
- using cross-validation
- engineering more features such as family size or title extraction
- improving class imbalance handling
