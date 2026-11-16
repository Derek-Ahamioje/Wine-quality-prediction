# Wine Quality Prediction

## Project Overview

This project investigates the relationship between physicochemical properties and wine quality using statistical analysis and machine learning techniques.

The objective was to identify the key factors influencing wine quality and evaluate the effectiveness of regression and classification models in predicting quality scores.

The project analysed a dataset containing 1,599 red wine samples and 11 physicochemical characteristics, including acidity, pH, alcohol content, sulphates, chlorides, and density.

---

## Business Problem

Wine producers need to understand how physicochemical characteristics influence quality in order to improve production processes and product consistency.

This project explores whether machine learning models can accurately predict wine quality and identify the most influential quality-driving factors.

---

## Dataset

### Source
Kaggle Wine Quality Dataset

### Dataset Characteristics

- 1,599 wine samples
- 11 physicochemical attributes
- 1 quality variable

### Features

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulphur Dioxide
- Total Sulphur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality

---

## Methodology

### Exploratory Data Analysis

The dataset was analysed to identify:

- Missing values
- Outliers
- Feature distributions
- Quality class distribution
- Correlations among variables

### Data Preprocessing

Several preprocessing techniques were applied:

- Data cleaning
- Feature scaling
- Data normalisation
- MinMaxScaler
- SMOTE oversampling

SMOTE was used to address class imbalance and improve dataset representation across wine quality categories.

### Feature Selection

SelectKBest was applied to identify the most influential variables contributing to quality prediction.

### Regression Models

The following regression models were developed and evaluated:

- Multiple Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- XGBoost Regression

### Classification Models

The following classification algorithms were evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbour (KNN)

---

## Key Findings

### Important Features

Feature importance analysis showed that the most influential quality indicators were:

- Volatile Acidity
- Alcohol
- Citric Acid
- Sulphates

### Regression Performance

| Model | Performance |
|---------|------------|
| Multiple Linear Regression | R² = 0.74 |
| Decision Tree Regression | R² = 0.85 |
| XGBoost Regression | R² = 0.95 |

XGBoost achieved the highest predictive performance with an R² score of 95% and the lowest prediction error.

### Classification Performance

| Model | Accuracy |
|---------|----------|
| Logistic Regression | 60% |
| Support Vector Machine (SVM) | 64% |
| K-Nearest Neighbour (KNN) | 61% |

Support Vector Machine (SVM) achieved the highest classification accuracy.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib
- Seaborn
- Google Colab

---

## Skills Demonstrated

- Machine Learning
- Regression Analysis
- Classification Modelling
- XGBoost
- Feature Engineering
- Feature Selection
- Data Preprocessing
- SMOTE
- Exploratory Data Analysis (EDA)
- Model Evaluation
- Statistical Analysis
- Python Programming

---

## Project Outcome

The project demonstrated that machine learning techniques can effectively predict wine quality from physicochemical characteristics.

Among all models tested, XGBoost delivered the strongest predictive performance, while Support Vector Machine achieved the best classification accuracy.

The findings suggest that alcohol concentration, volatile acidity, citric acid, and sulphates are among the most influential indicators of wine quality.

---

## Repository Structure

```text
wine-quality-prediction
│
├── data
├── images
├── notebook
├── reports
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Repository Contents

### Executive Summary
See `reports/Wine_Quality_Prediction_Executive_Summary.docx`

### Notebook
See `notebook/Wine_Quality_task_1_&_2.ipynb`

### Visualisations
See `images/`

### Dataset Information
See `data/`

---

## Author

**Derek Ahamioje**

Data Scientist | Research Analytics Specialist | Published Researcher | Computer Science Lecturer
