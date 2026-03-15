# 🧠 Medical Insurance Cost Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-Data%20Science-blue)
![Project](https://img.shields.io/badge/Project-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Level](https://img.shields.io/badge/Level-Intermediate-purple)
![Focus](https://img.shields.io/badge/Focus-Regression%20Model-yellow)

------------------------------------------------------------------------

## 👨‍💻 Author

**Ashish Jonnada**\
🎓 B.Tech CSE (AI & Data Science) --- Marwadi University

🔗 LinkedIn: [Ashish Jonnada](https://www.linkedin.com/in/jonnada-ashish)

------------------------------------------------------------------------

## 📌 Project Overview

This project focuses on predicting **medical insurance charges** using a
**Multiple Linear Regression model** based on demographic and
health-related features such as age, BMI, smoking status, number of
children, and region.

The objective of this project is to analyze the factors that influence
medical insurance costs and build a machine learning model capable of
estimating insurance charges.

------------------------------------------------------------------------

## ⚠️ Problem Statement

Medical insurance costs vary significantly depending on multiple
personal and lifestyle factors. Understanding these relationships is
important for predicting healthcare expenses and improving insurance
pricing strategies.

This project aims to analyze these factors and build a predictive model
for estimating insurance charges.

------------------------------------------------------------------------

## 🎯 Project Objectives

-   Understand the structure of the medical insurance dataset
-   Perform exploratory data analysis (EDA)
-   Identify relationships between features and insurance charges
-   Apply feature engineering techniques
-   Train a regression model to predict insurance costs
-   Evaluate model performance using multiple metrics
-   Analyze prediction errors using residual analysis

------------------------------------------------------------------------

## 🧠 Methodology

### 🔍 Data Understanding

-   Explored dataset structure and feature types
-   Analyzed numerical and categorical variables
-   Studied the distribution of insurance charges

### 📊 Exploratory Data Analysis

-   Distribution analysis of insurance charges
-   Relationship analysis between age, BMI, and charges
-   Comparison between smokers and non-smokers
-   Correlation heatmap of numerical features

### 🛠 Feature Engineering

New features were created: - BMI Category - Age Group - Health Risk
Level

### 🤖 Model Training

A **Multiple Linear Regression model** was trained using demographic and
health-related features.

------------------------------------------------------------------------

## 📈 Model Performance

| Metric | Value |
|------|------|
| R² Score | 0.83 |
| MAE | 3819 |
| MSE | 30301249 |
| RMSE | 5504 |

-----------------------------------------------------------------------
## ⚠️ Outlier Handling

During the analysis, some extreme values were observed in the insurance charges. These values represent real-world cases where individuals have very high medical expenses.

Instead of removing them, the outliers were kept in the dataset to preserve realistic data patterns. Removing these values could artificially improve model metrics but would reduce the model’s ability to capture extreme insurance costs.

Because of these extreme cases, the model shows slightly higher prediction errors for very high charges, which contributes to the final R² score of 0.83.

-----------------------------------------------------------------------
## 📊 Key Insights

-   Smoking status has the strongest impact on insurance charges.
-   Higher BMI levels are associated with increased insurance costs.
-   Age shows a positive relationship with insurance charges.
-   The model predicts moderate insurance charges more accurately than
    extreme values.

------------------------------------------------------------------------

## 🛠 Tools & Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn
-   Jupyter Notebook

------------------------------------------------------------------------

## 🏁 Conclusion

The Multiple Linear Regression model achieved an **R² score of 0.83**,
showing strong predictive capability for most cases. The project
demonstrates how machine learning can help analyze healthcare cost
patterns and predict insurance expenses.
