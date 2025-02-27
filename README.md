Iris Classification using Logistic Regression:

Overview:
This project demonstrates Iris flower classification using Logistic Regression from the scikit-learn library. The model predicts the species of an Iris flower based on sepal length and sepal width.

Dataset:
The dataset used is the Iris dataset, which consists of:
3 Classes: Setosa, Versicolor, Virginica
4 Features: Sepal Length, Sepal Width, Petal Length, Petal Width
150 Samples

Installation:
Make sure you have Python and the required libraries installed. You can install dependencies using:
pip install scikit-learn matplotlib

Running the Code:
Execute the following script to train and test the model:
python iris_classification.py

Code Explanation:
Load the Iris dataset
Select first two features (Sepal Length & Sepal Width)
Split the data into training (80%) and testing (20%)
Train a Logistic Regression model
Predict test results and compute accuracy
Visualize the results using a scatter plot

Expected Output:
Model Accuracy (Displayed in console)
Scatter plot of classification results
