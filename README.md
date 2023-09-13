# Pima Indians Diabetes Dataset (Kaggle)
Pima Indians Diabetes Dataset (Kaggle) analysis

![Kaggle logo](/Codes/kagglelogo.png)

This repository contains code and documentation for the "Pima Indians Diabetes Dataset" from Kaggle. The dataset is used for the Data Mining Course by me.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data](#data)
- [Data Preprocessing](#data-preprocessing)
  - [Handling Missing Values](#handling-missing-values)
  - [Handling Outliers](#handling-outliers)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
  - [Decision Tree Classifier](#decision-tree-classifier)
  - [Random Forest Classifier](#random-forest-classifier)
  - [Cross-Validation](#cross-validation)
- [Model Evaluation](#model-evaluation)
  - [Confusion Matrix](#confusion-matrix)
  - [Receiver Operating Characteristic (ROC)](#receiver-operating-characteristic-roc)
- [Conclusion](#conclusion)

## Introduction

The Pima Indians Diabetes Dataset is a well-known dataset in the field of data mining and machine learning. It contains various features related to Pima Indian women, along with a binary target variable indicating whether or not the individual has diabetes. This repository explores the dataset, preprocesses the data, builds and evaluates machine learning models, and provides insights into model performance.

## Getting Started

### Prerequisites

Before running the code in this repository, make sure you have the following libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install them using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Installation
To get started, clone this repository to your local machine:

```bash
git clone https://github.com/hossein-zandinejad/Pima-Indians-Diabets-Dataset-Kaggle-
```
## Data

The dataset used in this project is "diabetes.csv," which contains various features such as age, BMI, blood pressure, and more, along with the target variable "Outcome" (0 for non-diabetic, 1 for diabetic).

## Data Preprocessing

### Handling Missing Values

The dataset is checked for missing values, and it is confirmed that there are no missing values.

### Handling Outliers

Outliers in the "BMI" column are identified using the Interquartile Range (IQR) method and removed from the dataset.

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) is performed to gain insights into the data, including data distribution, correlations, and visualizations. Various plots and visualizations are created to better understand the dataset.

## Modeling

Two machine learning models are implemented for classification:

### Decision Tree Classifier

A Decision Tree Classifier is trained on the dataset, and its accuracy is evaluated. A C4.5 version of the Decision Tree is also trained and evaluated.

### Random Forest Classifier

A Random Forest Classifier is trained on the dataset, and its accuracy is evaluated.

### Cross-Validation

Cross-validation is performed for all models using k-fold cross-validation to assess their generalization performance.

## Model Evaluation

### Confusion Matrix

Confusion matrices are generated for each model to visualize their performance in terms of true positives, true negatives, false positives, and false negatives.

### Receiver Operating Characteristic (ROC)

ROC curves are plotted for each model, and the ROC AUC scores are calculated to compare the performance of the models in terms of their ability to distinguish between positive and negative classes.

## Conclusion

Based on the analysis and evaluation of the models, it is concluded that the Random Forest model performs better than the Decision Tree model for this dataset. The ROC AUC score indicates that the Random Forest model has better discriminatory power.

Feel free to explore the code and documentation in this repository for more details on the analysis and results.

If you have any questions or suggestions, please contact me.
