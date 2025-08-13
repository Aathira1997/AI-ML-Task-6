## AI-ML-Task-6

## K-Nearest Neighbors (KNN) Classification

## Overview
This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm for classification tasks using the Iris dataset. 
## Dataset
The dataset used in this project is the Iris dataset, which contains measurements of iris flowers from three different species (Iris-setosa, Iris-versicolor, and Iris-virginica).

## Tools and Libraries
Python

Pandas

NumPy

Matplotlib

Scikit-learn

## Steps

1. Import the Dataset
   
Load the dataset using Pandas and explore its structure and data types.

Check for missing values and dataset statistics.

2. Normalize Features
   
Use StandardScaler from scikit-learn to standardize numerical features so that they have zero mean and unit variance.

3. Encode Target Variable
   
Use LabelEncoder to convert species names into numeric class labels.

4. Split Dataset
   
Use train_test_split to divide the data into training (70%) and testing (30%) sets.

5. Train and Evaluate KNN Classifier
   
Train the KNeighborsClassifier for multiple values of K.

Predict on the test set and compute accuracy scores.

Generate and display confusion matrices for each K.

6. Visualize Decision Boundaries
   
Select a value of K (e.g., K=5).

Plot decision boundaries using the first two features for a 2D visualization.

Use matplotlib contour plots and scatter plots to show the separation between classes.

## Output

Accuracy scores for different K values.

Confusion matrix visualizations for each K.

Decision boundary plot for chosen K.

