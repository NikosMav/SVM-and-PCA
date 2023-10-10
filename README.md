# Machine Learning Exercise

## 3rd Programming Assignment

## Overview

This Python notebook contains the code and documentation for the 3rd programming assignment for the "Μηχανική Μάθηση" (Machine Learning) course (ΕΠ08) at NKUA. In this assignment, we perform various tasks related to machine learning, including data preprocessing, hyperparameter tuning, SVM classification, and dimensionality reduction using PCA (Principal Component Analysis).

## Getting Started

To run this notebook, follow these steps:

1. Mount Google Drive: Before starting, you need to mount your Google Drive to access the necessary data files. The code for mounting Google Drive is provided in the notebook.

2. Data Files: The assignment assumes the presence of two data files: `mnist_test.csv` and `mnist_train.csv`. Make sure these files are available in your Google Drive at the specified paths.

3. Dependencies: Ensure that you have the required Python libraries installed, such as NumPy, pandas, scikit-learn, and others. You can install these libraries using pip or conda.

## Notebook Structure

### 1. Importing Libraries and Preparing the Data

This section includes importing necessary libraries and reading the data files into Pandas DataFrames. It also normalizes the datasets.

### 2. Split Datasets

In this section, we split the datasets into training and testing sets.

### 3. Hyperparameter Tuning

We perform hyperparameter tuning for an SVM (Support Vector Machine) classifier using GridSearchCV. The best parameters are determined for the SVM model.

### 4. SVM Classifier

We train an SVM classifier using the best parameters obtained from hyperparameter tuning. The classifier is evaluated on the test dataset, and classification metrics such as precision, recall, and F1-score are calculated.

### 5. PCA Process

In this section, we perform dimensionality reduction using PCA. We reduce the dataset to different percentages of sustained covariance (0.95 and 0.75) and evaluate the SVM classifier's performance on the reduced datasets.

## Results

The results of the SVM classifier and dimensionality reduction experiments are provided in the notebook. These results include accuracy, precision, recall, F1-score, and the execution time for each experiment.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
