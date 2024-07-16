# Rain Prediction in Australia using Classification

This project is the culmination of the machine learning coursework for IBM's Machine Learning with Python.   
It's focused on predicting rain in Australia using various classification algorithms.   
Below is a summary designed to guide you through understanding, setting up, and operating this project.

## Table of Contents
1. [Instructions](#Instructions)
2. [About the Data](#About-the-Data)
3. [Importing Data](#Importing-Data)
4. [Data Preprocessing](#Data-Preprocessing)
5. [Training and Testing](#Training-and-Testing)
6. [Results and Performance Metrics](#Results-and-Performance-Metrics)

### Instructions
This notebook includes practical application of classification algorithms learned during the course.   
The following algorithms were used to train models based on the Australian weather dataset and subsequently evaluate their performance:

- Linear Regression
- KNN (K-Nearest Neighbors)
- Decision Trees
- Logistic Regression
- SVM (Support Vector Machine)

For evaluation, the following metrics are calculated:
- Accuracy Score
- Jaccard Index
- F1-Score
- LogLoss (specifically for Logistic Regression)
- Mean Absolute Error
- Mean Squared Error
- R2-Score

This hands-on experience aims to solidify your understanding of how these models work, how to train them, and how to interpret their performance metrics.

### About the Data
The dataset spans from 2008 to 2017, comprising daily weather observations across Australia. The primary objective is to predict the variable 'RainTomorrow', indicating whether it will rain the next day. The dataset was sourced from the Australian Government's Bureau of Meteorology and modified for our specific use-case with additional variables like 'RainToday'.

### Importing Data
Data is fetched from a predefined URL and loaded into a Pandas DataFrame, making it ready for preprocessing and analysis.

### Data Preprocessing
The preprocessing steps include One Hot Encoding to transform categorical variables into a binary format and splitting the 'RainTomorrow' column from categorical to binary. This conversion is crucial for the models to process the data correctly.

### Training and Testing
The dataset is divided into training and test sets, ensuring that the models are evaluated on unseen data, thus providing a genuine insight into their performance. The `train_test_split` function facilitates this, with a designated test size of 20%.

### Results and Performance Metrics
Each trained model is evaluated based on accuracy, Jaccard index, F1-score, and LogLoss metrics. The Logistic Regression model also includes evaluation on Mean Absolute Error, Mean Squared Error, and R2-Score. Results are presented in a tabular format for clear and concise comparison.

## Getting Started
To get started with this project, clone the repository and follow the instructions in the notebook. Ensure you have the necessary Python libraries installed, including Pandas, Numpy, Scikit-learn, Matplotlib, and Seaborn.

This project serves not only as a practical application of machine learning classification algorithms but also as a template for similar predictive modeling tasks. Whether for educational purposes or extending to more complex datasets, the foundational work laid out here should provide a solid starting point.

---

Zak Mohamed | July 2024
