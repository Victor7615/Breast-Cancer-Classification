# Breast Cancer Prediction Model

This repository contains a machine learning model developed to predict whether a cell is benign or malignant based on breast cancer dataset. The model utilizes various classification algorithms such as Logistic Regression, Decision Tree, K Nearest Neighbor (KNN), Naive Bayes, and Support Vector Machine (SVM) to classify cells into benign or malignant categories.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Models](#models)
  - [Logistic Regression](#logistic-regression)
  - [Decision Tree](#decision-tree)
  - [K Nearest Neighbor (KNN)](#k-nearest-neighbor-knn)
  - [Naive Bayes](#naive-bayes)
  - [Support Vector Machine (SVM)](#support-vector-machine-svm)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Breast cancer is one of the most common cancers among women worldwide. Early detection of breast cancer significantly improves treatment outcomes. Machine learning models can assist in the early detection process by analyzing various features of cells to predict whether they are benign or malignant.

This repository demonstrates the development and evaluation of machine learning models for breast cancer prediction using the Wisconsin Breast Cancer dataset. The goal is to create a robust predictive model that can accurately classify breast cells as benign or malignant.

## Dataset

The dataset used in this project is the Wisconsin Breast Cancer dataset. It contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. Each feature represents various characteristics of cell nuclei present in the image.

## Preprocessing

Before building the predictive models, the dataset undergoes preprocessing steps, including:
- Removing unnecessary columns such as 'id' and 'Unnamed: 32'.
- Encoding the target variable ('diagnosis') to binary values (0 for benign, 1 for malignant).
- Splitting the dataset into features (independent variables) and labels (dependent variable).

## Models

The following machine learning models are implemented and evaluated in this project:

### Logistic Regression

Logistic regression is a classification algorithm used to model the probability of a certain class or event. It's a popular choice for binary classification tasks.

### Decision Tree

Decision tree is a versatile algorithm used for both classification and regression tasks. It partitions the feature space into regions and predicts the target variable based on the majority class or average value within each region.

### K Nearest Neighbor (KNN)

KNN is a non-parametric classification algorithm that classifies a data point based on the majority class of its 'k' nearest neighbors in the feature space.

### Naive Bayes

Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem with an assumption of independence between features.

### Support Vector Machine (SVM)

SVM is a powerful classification algorithm that finds the hyperplane that best separates the classes in the feature space.

## Results

The models are evaluated based on various metrics such as accuracy, cross-validation scores, confusion matrices, classification reports, and ROC curves. The performance of each model is assessed to determine its effectiveness in predicting breast cancer.

## Contributing

Contributions to this repository are welcome. If you have any suggestions for improvements or new features, feel free to open an issue or submit a pull request.





