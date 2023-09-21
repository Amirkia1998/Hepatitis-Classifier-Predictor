# Hepatitis Prediction

This project applies three different classification methods (K Nearest Neighbor, Decision Tree, and Naive Bayes) to the UCI ML Hepatitis dataset. The goal is to predict whether or not a patient will die from hepatitis. This project was developed as part of the course "Information Retrieval & Web Search Engines."

## About the Dataset

The UCI ML Hepatitis dataset contains information about patients with hepatitis. It includes various attributes such as age, sex, bilirubin levels, and more. The target variable indicates whether a patient will live or die from hepatitis.

## Classification Methods

### 1. K Nearest Neighbor (K-NN)

- The K-NN classifier is used to predict outcomes based on the similarity of data points.
- You can adjust the number of neighbors (K) to fine-tune the model's performance.
- The GUI allows you to visualize accuracy and make predictions for new data.

### 2. Decision Tree

- The Decision Tree classifier creates a tree-like model to make predictions.
- It's capable of handling both numerical and categorical data.
- The GUI provides accuracy metrics and prediction capabilities.

### 3. Naive Bayes

- The Naive Bayes classifier is a probabilistic algorithm.
- It's suitable for datasets with categorical features.
- You can evaluate its performance and make predictions using the GUI.

## Getting Started

1. Clone this repository to your local machine.
2. Install the required dependencies, including PyQt5, NumPy, Matplotlib, and scikit-learn.
3. Run the GUI application by executing the main Python file.

## Usage

- Launch the GUI application, which provides options to select classification methods, set parameters, and make predictions.
- Load your data or use the provided sample dataset.
- Explore the accuracy of each classifier and predict outcomes for new data.
- To predict a single patient's outcome, put the patient's data in the `predict.txt` file and use the GUI's prediction functionality.

## Predicting a Single Patient

To predict the outcome for a single patient:
1. Open the `predict.txt` file.
2. Enter the patient's data in the required format.
3. Save the file.
4. Use the GUI's prediction feature to predict the outcome for the patient based on the provided data.

## Acknowledgments

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/hepatitis) for providing the Hepatitis dataset.

