Iris Dataset Machine Learning Project

Overview

This repository contains a machine learning project focused on the famous Iris dataset. The dataset consists of measurements of various features of iris flowers, including Sepal Length, Sepal Width, Petal Length, Petal Width, and the species of the iris. The goal of this project is to explore and implement various machine learning algorithms to identify the best model for predicting the iris species based on the given features.

Dataset

The dataset contains the following columns:

Id: Unique identifier for each observation Sepal.Length: Length of the sepal in centimeters Sepal.Width: Width of the sepal in centimeters Petal.Length: Length of the petal in centimeters Petal.Width: Width of the petal in centimeters Species: The species of the iris (setosa, versicolor, or virginica)

Exploratory Data Analysis

The notebooks in the 'notebooks' directory cover the exploratory data analysis process, including visualizations and statistical summaries of the dataset.

Data Preprocessing

The 'src' directory contains Python scripts for data preprocessing, such as handling missing values, encoding categorical variables, and scaling numerical features.

Model Development

Various machine learning algorithms, such as Decision Trees, Random Forest, Support Vector Machines, and K-Nearest Neighbors, have been implemented and evaluated. The model training and evaluation code can be found in the 'notebooks' and 'src' directories.

Model Evaluation

The performance of each model is assessed using appropriate evaluation metrics, such as accuracy, precision, recall, and F1 score. The results are discussed in the notebooks.

Conclusion

Based on the evaluation results, the best-performing machine learning model for predicting iris species is identified. The selected model is then saved in the 'models' directory.
