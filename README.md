# Breast Cancer Wisconsin (Diagnostic) Classification

## Overview
This repository contains a machine learning program designed to classify breast cancer tumors as malignant or benign using two different models: Logistic Regression and Support Vector Machine (SVM). The models are trained on the well-known Breast Cancer Wisconsin (Diagnostic) dataset, and their performance is evaluated based on standard metrics.

## Dataset
The Breast Cancer Wisconsin (Diagnostic) dataset is used in this project. It includes features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The target variable indicates whether the tumor is malignant (1) or benign (0).

## Models

### Logistic Regression
Logistic Regression is a commonly used classification algorithm that models the probability of a binary outcome. In this project, Logistic Regression is applied to predict whether a tumor is malignant or benign based on the input features.

### Support Vector Machine (SVM)
Support Vector Machines are powerful classifiers that aim to find the hyperplane that best separates the classes in the feature space. Here, we use a linear kernel SVM to classify breast cancer tumors.

## Usage

### Dependencies
- Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
