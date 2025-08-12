# Task-6

Task 6: KNN Classification on Iris Dataset

This project demonstrates the K-Nearest Neighbors (KNN) classification algorithm applied to the well-known Iris dataset, which contains measurements of iris flowers from three species (Iris-setosa, Iris-versicolor, Iris-virginica). The goal is to predict the flower species based on sepal length, sepal width, petal length, and petal width.

Key Steps in the Code
1. Dataset Loading

Reads the provided Iris.csv file using pandas.

Displays the first few rows for an initial look at the dataset.

2. Data Preprocessing

Identifies the target column (Species) and separates it from the feature columns.

Encodes the species names into numerical labels using LabelEncoder.

Standardizes all features using StandardScaler to ensure equal weight in distance calculation.

3. Train/Test Split

Splits the dataset into 70% training and 30% testing sets.

Uses stratified sampling to keep class proportions consistent in both sets.

4. Model Training & Hyperparameter Tuning

Trains multiple KNN models with different values of k (from 1 to 15).

Records accuracy for each k and selects the best k based on test accuracy.

5. Model Evaluation

Evaluates the final model using accuracy, precision, recall, and F1-score.

Displays a confusion matrix to show correct vs. incorrect predictions for each class.

6. Visualization

Accuracy vs. k plot to illustrate how accuracy changes with different k values.

Confusion matrix heatmap for performance overview.

Decision boundary plot using the first two features to visually separate classes.

7. Purpose
This project is useful for:

Understanding how KNN works for classification tasks.

Learning the importance of feature scaling in distance-based models.

Observing the impact of k-value selection on model accuracy.

Gaining practical experience with classification evaluation metrics and visualization.
