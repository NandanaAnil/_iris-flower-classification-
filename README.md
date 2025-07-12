 Iris Flower Classification using Machine Learning
 
This project demonstrates how to classify iris flowers into species using three supervised machine learning algorithms:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

 Dataset
The model uses the Iris dataset, a classical dataset that contains 150 samples of iris flowers with 4 features:

Sepal length

Sepal width

Petal length

Petal width
Each sample belongs to one of three classes: Iris-setosa, Iris-versicolor, or Iris-virginica.

  Workflow Summary
Data Import & Visualization

Load the Iris dataset using seaborn.

Display data types and correlation matrix to understand feature relationships.

Preprocessing

Split the dataset into training and testing sets using train_test_split.

Model Training & Evaluation

Logistic Regression: Trains a simple linear model and prints accuracy.

Decision Tree: Builds a tree-based model to classify flowers and evaluates performance.

Random Forest: Trains an ensemble of decision trees and compares accuracy.

Each model’s accuracy is printed, allowing you to compare performance across the three algorithms.
