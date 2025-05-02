# Comprehensive Machine Learning and Data Mining Analysis: IBM HR Attrition, Medical Costs, and Association Rule Mining

## Project Overview

This project involves the application of machine learning and data mining techniques across three unique datasets to solve real-world business problems. The analyses focus on understanding employee attrition, predicting medical insurance costs, and identifying associations between customer viewing preferences.

## Introduction

This project demonstrates the use of supervised and unsupervised machine learning techniques, as well as association rule mining, to derive meaningful insights from three datasets:

- **IBM HR Attrition Dataset**: K-means clustering and DBSCAN clustering predict employee attrition.
- **Medical Cost Dataset**: A regression task to predict health insurance charges.
- **Customer Viewing Dataset**: An association rule mining task to identify viewer preferences.

The goal is to apply appropriate machine learning techniques, optimize models, and provide actionable insights for decision-making.

## Datasets

- **IBM HR Attrition Dataset**: Contains features such as age, work experience, job level, overtime status, and attrition.
- **Medical Cost Dataset**: Includes demographic and lifestyle features (e.g., age, BMI, smoking status) and the target variable, charges.
- **Customer Viewing Dataset**: Contains viewing preferences for various shows.

## Part 1: IBM HR Attrition Case Study

### Objective
Predict employee attrition and identify key factors influencing it.

### Techniques
- **Data Preprocessing**: Conversion of categorical features into numerical, removal of low-correlation features.
- **Visualization**: Box plots, bar plots, and correlation heatmaps to identify key factors such as overtime and salary.

### Classification Models:
- **Random Forest**: Achieved 86.14% accuracy.
- **K-Nearest Neighbors (KNN)**: Achieved 84.51% accuracy.
- **Support Vector Machine (SVM)**: Achieved 86% accuracy.
- **Clustering**: Applied k-means and DBSCAN clustering to identify employee groups based on income and tenure.


## Requirements
- **Python 3.7** or higher
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `mlxtend`
