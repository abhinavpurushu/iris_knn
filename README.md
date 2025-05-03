# Iris Dataset Classification using K-Nearest Neighbors (KNN)

## Overview
This project implements the K-Nearest Neighbors (KNN) algorithm to classify species in the Iris dataset. It includes data preprocessing, model training, evaluation across various k values, and visualization of decision boundaries using both feature pairs and Principal Component Analysis (PCA).

## Dataset
Source: Iris Dataset from Kaggle (This is the famous Iris dataset which was used in R.A. Fisher's classic 1936 paper).
Features: 4 Features (Sepal Length, Sepal Width, Petal Length, Petal Width)

Target: Species (Setosa, Versicolor, Virginica)

## Steps Covered
1. Imported Necessary Libraries
2. Loaded the dataset using pandas.
3. Separated features and target variable.
4. Standardized features using StandardScaler.
5. Split the dataset into training and testing sets (80-20 split).
6. Trained KNN models for k values ranging from 1 to 20.
7. Evaluated models using accuracy scores and confusion matrices.
8. Identified the optimal k value based on test accuracy.
9. Plotted accuracy vs. k to observe performance trends.
10. Visualized decision boundaries using:
a. Sepal features (Sepal Length vs. Sepal Width).
b. Petal features (Petal Length vs. Petal Width).
c. PCA-reduced features (Principal Component 1 vs. Principal Component 2).

## Results
Optimal k Value: 1 (Determined based on highest test accuracy.)

Model Performance: Achieved high accuracy with clear class separation.

Visual Insights:
1. Decision boundaries effectively separate species.
2. PCA visualization captures the majority of variance, providing a comprehensive view of class separability.
