# AI-ML-TASK-6
 AI & ML Internship - Task 6: K-Nearest Neighbors (KNN) Classification
 Objective
Implement and evaluate the K-Nearest Neighbors (KNN) algorithm for classification tasks using the Iris dataset. This project focuses on:

Training and testing a KNN model
Experimenting with different values of K
Evaluating model performance
Visualizing decision boundaries
 Tools & Libraries
Python
Google Colab
Scikit-learn
Pandas
Matplotlib
NumPy
 Dataset
Iris.csv
Contains measurements of iris flowers from three species: Iris-setosa, Iris-versicolor, and Iris-virginica.

 Implementation Steps
Load and clean the Iris dataset.
Normalize the feature values using StandardScaler.
Split the dataset into training and testing sets (80/20).
Train KNeighborsClassifier using Scikit-learn.
Evaluate the model using:
Accuracy score
Confusion matrix
Classification report
Visualize decision boundaries using only two features for 2D plotting.
 Results
Achieved 100% accuracy for multiple values of K (K = 2 to 10).
Confusion matrix shows perfect classification.
Decision boundary plot clearly shows well-separated classes.
 How to Run (in Google Colab)
Upload Iris.csv when prompted.
Execute all cells step-by-step.
Observe K-wise accuracy, confusion matrix, classification report, and decision boundary plot.
Sample Output
K = 3 → Accuracy: 1.00

Confusion Matrix: [[10 0 0] [ 0 9 0] [ 0 0 11]
