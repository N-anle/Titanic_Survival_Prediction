# Titanic Survival Prediction 🚢

This project is an exploration of the famous Titanic dataset, where the goal is to predict the survival of passengers based on various features, including gender, age, class, and embarkation station.

## Overview

In this project, I perform basic data cleaning, exploratory data analysis (EDA), and machine learning to predict survival outcomes. I start by cleaning the dataset, handling missing values, and transforming categorical data into a format that can be processed by machine learning algorithms.

I then use a few machine learning models, including K-Nearest Neighbors (KNN), Random Forests, and Gradient Boosting to make predictions. The model's performance is evaluated through accuracy, confusion matrices, and classification reports.

## Dataset

The dataset used is the Titanic dataset from Kaggle, which contains information about passengers aboard the RMS Titanic, including:

- `Name`: The name of the passenger
- `Age`: The age of the passenger
- `Fare`: The fare paid by the passenger
- `Sex`: The gender of the passenger
- `Embarked`: The port where the passenger boarded
- `Pclass`: The class of the cabin the passenger stayed in
- `Survived`: Whether the passenger survived (1) or did not survive (0)

## Approach

1. **Data Cleaning**: Dropped duplicate rows, handled missing values (e.g., filled missing ages with the mean), and converted categorical variables into numerical ones.
2. **Exploratory Data Analysis (EDA)**: Analyzed the dataset for key insights, such as survival rates based on gender and class.
3. **Machine Learning**:
   - K-Nearest Neighbors (KNN): Used to predict survival outcomes based on available features.
   - Random Forests & Gradient Boosting: Attempted to further refine the model but encountered overfitting (100% accuracy).
4. **Evaluation**: Assessed model performance using accuracy, confusion matrices, and classification reports.

## Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib (optional for visualizations)

## Installation

Clone the repository:
```bash
git clone https://github.com/N-anle/Titanic_Survival_Prediction.git
