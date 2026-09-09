#      **** ML PRACTICALS ****

# PRACTICAL 1 

# Logistic Regression – Advertisement Click Prediction

This project implements a **Logistic Regression machine learning model** to predict whether a user will click on an advertisement based on their online activity. The model uses two important features: **Daily Time Spent on Site** and **Daily Internet Usage** to perform binary classification.

The project demonstrates a complete machine learning workflow, starting from data loading and Exploratory Data Analysis (EDA) to model training, prediction, evaluation, and visualization.

## Project Workflow

The dataset is first loaded using **Pandas** from the `advertising.csv` file. Basic information about the dataset is explored, including its shape, column names, data types, missing values, statistical summary, and target class distribution.

Exploratory Data Analysis is performed using **Matplotlib** and **Seaborn**. Visualizations such as the target distribution and correlation heatmap are used to understand the dataset and relationships between numerical features.

For model building, **Daily Time Spent on Site** and **Daily Internet Usage** are selected as input features, while **Clicked on Ad** is used as the target variable. The data is divided into training and testing sets using `train_test_split`. **StandardScaler** is then applied to scale the input features.

A **Logistic Regression** model from Scikit-learn is trained using the scaled training data. The trained model is used to predict both the class labels and probability of an advertisement click.

The model performance is evaluated using several important classification metrics, including **Accuracy, Confusion Matrix, Classification Report, ROC Curve, and AUC Score**. These evaluation techniques help measure how effectively the model distinguishes between users who click and do not click on advertisements.

The project also visualizes the **Decision Boundary** of the Logistic Regression model to show how the two selected features separate the classes. Additionally, the **Sigmoid Function** is visualized to demonstrate how Logistic Regression converts the linear predictor into a probability between 0 and 1.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy

## Objective

The main objective of this project is to understand and implement **Logistic Regression for binary classification**, analyze its predictions, and evaluate its performance using different machine learning evaluation techniques.


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



# PRACTICAL 2

# ML-Practical-2-Linear-Regression
Implementation of Simple and Multiple Linear Regression using NumPy and Scikit-Learn with Residual Plots, RMSE, and R2 evaluation.
