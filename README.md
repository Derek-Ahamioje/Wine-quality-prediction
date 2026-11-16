**Wine Quality Prediction**

**Project Overview**

This project investigates the relationship between physicochemical properties and wine quality using statistical analysis and machine learning techniques.

The objective was to identify the key factors influencing wine quality and evaluate the effectiveness of regression and classification models in predicting quality scores.

The project analysed a dataset containing 1,599 red wine samples and 11 physicochemical characteristics including acidity, pH, alcohol content, sulphates, chlorides, and density.

**Business Problem**

Wine producers need to understand how physicochemical characteristics influence quality in order to improve production processes and product consistency.

This project explores whether machine learning models can accurately predict wine quality and identify the most influential quality-driving factors.

**Dataset**

Source: Kaggle Wine Quality Dataset

**Dataset Characteristics:**

1,599 wine samples
11 physicochemical attributes
1 quality variable

**Features include:**

Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulphur dioxide
Total sulphur dioxide
Density
pH
Sulphates
Alcohol
Quality

**Methodology**

**Exploratory Data Analysis**

The dataset was analysed to identify:

Missing values
Outliers
Feature distributions
Quality class distribution
Correlations among variables

**Data Preprocessing**

Several preprocessing techniques were applied:

Data cleaning
Feature scaling
Data normalisation
MinMaxScaler
SMOTE oversampling
SMOTE was used to address class imbalance and increase dataset representation across wine quality categories.

**Feature Selection**

SelectKBest was applied to identify the most influential variables contributing to quality prediction.

**Regression Models**

The following models were evaluated:

Multiple Linear Regression
Ridge Regression
Lasso Regression
Decision Tree Regression
XGBoost Regression

**Classification Models**

The following models were evaluated:

Logistic Regression
Support Vector Machine (SVM)
K-Nearest Neighbour (KNN)

**Key Findings**

**Important Features**

Feature importance analysis showed that the most influential quality indicators were:

Volatile Acidity
Alcohol
Citric Acid
Sulphates

**Model Performance**

Model	Performance
Multiple Regression	R² = 0.74
Decision Tree	R² = 0.85
XGBoost	R² = 0.95
XGBoost achieved the highest predictive performance with an R² score of 95% and the lowest prediction error.

**Classification Results**

Model	Accuracy
Logistic Regression	60%
SVM	64%
KNN	61%
Support Vector Machine produced the best classification performance.

**Technologies Used**

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Matplotlib
* Seaborn
* Google Colab

**Skills Demonstrated**

* Machine Learning
* Regression Analysis
* Classification Modelling
* XGBoost
* Feature Engineering
* Feature Selection
* Data Preprocessing
* SMOTE
* Exploratory Data Analysis
* Model Evaluation
* Statistical Analysis
* Python

**Project Outcome**

The project demonstrated that machine learning can effectively predict wine quality from physicochemical attributes.

Among all models tested, XGBoost delivered the strongest predictive performance, while Support Vector Machine achieved the best classification accuracy.

The findings suggest that alcohol concentration, volatile acidity, citric acid, and sulphates are among the most influential wine quality indicators.

**Author**

Derek Ahamioje

Data Scientist | Research Analytics Specialist | Published Researcher | Computer Science Lecturer
