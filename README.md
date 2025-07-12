Iris Flower Classification using Machine Learning

This project showcases the application of three popular supervised machine learning algorithms to classify iris flowers based on their physical characteristics. The goal is to accurately predict the species of an iris flower using simple, yet powerful, classification techniques.

Algorithms Used
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
These models are evaluated based on their accuracy to provide a comparative understanding of their performance.

Dataset
We utilize the well-known Iris dataset, a benchmark dataset in machine learning that includes:
150 samples of iris flowers
4 features for each sample:
Sepal Length
Sepal Width
Petal Length
Petal Width
3 target classes:
1. Iris-setosa
2. Iris-versicolor
3. Iris-virginica
The dataset is loaded directly from the seaborn library for ease of use.

Workflow Overview

1. Data Loading & Visualization
Load the dataset using seaborn
Display data types and structure
Plot a correlation matrix to explore feature relationships

2. Preprocessing
Split the dataset into training and testing sets using train_test_split

3. Model Training & Evaluation
Logistic Regression: Train a linear model and calculate accuracy

Decision Tree Classifier: Create a tree-based model and evaluate its performance
Random Forest Classifier: Build an ensemble model and compare its results
Each model's accuracy is printed, providing insights into the strengths and weaknesses of different algorithms for this classification task.
