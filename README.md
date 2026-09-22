#      **** ML PRACTICALS ****

# PRACTICAL 1

# ML Practical 1 – Linear Regression

---

## 📌 Overview

This practical focuses on the implementation of **Simple Linear Regression** and **Multiple Linear Regression** using **Python, NumPy, and Scikit-Learn**.

It covers the complete regression workflow, including **data preparation, model training, prediction, visualization, residual analysis, and model evaluation**.

---

## 🎯 Objectives

* Implement **Simple Linear Regression** using NumPy.
* Implement Linear Regression using Scikit-Learn.
* Implement **Multiple Linear Regression**.
* Understand the relationship between independent and dependent variables.
* Visualize regression results using plots.
* Analyze prediction errors using residual plots.
* Evaluate model performance using **RMSE and R² Score**.

---

## 📚 Concepts Covered

### 1. Simple Linear Regression

Simple Linear Regression uses a **single independent variable** to predict a continuous dependent variable.

**Equation:**

`y = b₀ + b₁x`

**Where:**

* `y` → Predicted output
* `x` → Input feature
* `b₀` → Intercept
* `b₁` → Regression coefficient

### 2. Multiple Linear Regression

Multiple Linear Regression uses **multiple independent variables** to predict a continuous target variable.

**Equation:**

`y = b₀ + b₁x₁ + b₂x₂ + ... + bₙxₙ`

---

## ⚙️ Implementation

The practical includes:

* Data loading and preprocessing
* Exploratory Data Analysis (EDA)
* Feature and target selection
* Train-test splitting
* Simple Linear Regression using NumPy
* Linear Regression using Scikit-Learn
* Multiple Linear Regression
* Model prediction
* Regression line visualization
* Residual plot analysis
* Model performance evaluation

---

## 📊 Model Evaluation

### RMSE – Root Mean Squared Error

RMSE measures the average magnitude of prediction errors.

**Lower RMSE indicates better prediction performance.**

### R² Score – Coefficient of Determination

R² Score indicates how well the regression model explains the variation in the target variable.

**A value closer to 1 generally indicates a better model fit.**

---

## 📈 Residual Analysis

Residuals represent the difference between actual and predicted values.

**Residual = Actual Value − Predicted Value**

A residual plot helps analyze whether the prediction errors are randomly distributed around zero and helps identify patterns in model errors.

---

## 🛠️ Libraries Used

| Library          | Purpose                               |
| ---------------- | ------------------------------------- |
| **NumPy**        | Numerical computations                |
| **Pandas**       | Data manipulation and analysis        |
| **Matplotlib**   | Data visualization                    |
| **Scikit-Learn** | Machine learning model implementation |

---

## 📂 Project Structure

```text
ML-Practical-2-Linear-Regression/
│
├── Simple_Linear_Regression.ipynb
├── Multiple_Linear_Regression.ipynb
├── README.md
│
└── dataset/
    └── dataset.csv
```

---

## 💻 Requirements

Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## ▶️ Execution

1. Open the required Jupyter Notebook.
2. Load the dataset.
3. Perform data preprocessing and feature selection.
4. Split the dataset into training and testing sets.
5. Train the regression model.
6. Generate predictions.
7. Visualize the regression results and residuals.
8. Evaluate the model using **RMSE and R² Score**.

---

## ✅ Expected Outcomes

After completing this practical, the implementation demonstrates:

* Simple Linear Regression
* Multiple Linear Regression
* Regression visualization
* Residual analysis
* RMSE-based evaluation
* R² Score-based evaluation

---

## 📝 Conclusion

This practical provides an understanding of **Linear Regression** and its implementation using **NumPy and Scikit-Learn**, along with techniques for **visualizing, analyzing, and evaluating regression models**.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# ML Practical 2 – Logistic Regression

---

## 📌 Overview

This practical demonstrates the implementation of **Logistic Regression** for **binary classification** using Python and Scikit-Learn.

The model predicts whether a user will **click on an advertisement** based on their online activity, using **Daily Time Spent on Site** and **Daily Internet Usage** as input features.

---

## 🎯 Objective

The main objective of this practical is to understand and implement **Logistic Regression for binary classification**, make predictions, and evaluate the model using different classification evaluation techniques.

---

## 🔄 Project Workflow

The practical follows a complete machine learning workflow:

### 1. Data Loading

The dataset is loaded using **Pandas** from the `advertising.csv` file.

Basic information about the dataset is explored, including:

* Dataset shape
* Column names
* Data types
* Missing values
* Statistical summary
* Target class distribution

### 2. Exploratory Data Analysis

**Matplotlib** and **Seaborn** are used for Exploratory Data Analysis (EDA).

The practical includes visualizations such as:

* Target class distribution
* Correlation heatmap
* Relationships between numerical features

### 3. Feature Selection

The following features are selected for model training:

**Input Features:**

* Daily Time Spent on Site
* Daily Internet Usage

**Target Variable:**

* Clicked on Ad

The dataset is divided into training and testing sets using `train_test_split`.

**StandardScaler** is applied to scale the input features.

### 4. Model Training

A **Logistic Regression** model from Scikit-Learn is trained using the scaled training data.

The trained model is used to generate:

* Predicted class labels
* Probability of advertisement clicks

### 5. Model Evaluation

The model is evaluated using the following classification metrics:

* **Accuracy**
* **Confusion Matrix**
* **Classification Report**
* **ROC Curve**
* **AUC Score**

These metrics help measure how effectively the model distinguishes between users who click and do not click on advertisements.

### 6. Visualization

The practical also includes visualization of:

* **Decision Boundary** – Shows how the selected features separate the two classes.
* **Sigmoid Function** – Demonstrates how Logistic Regression converts the linear output into a probability between 0 and 1.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-Learn**
* **SciPy**

---

## 📚 Key Concepts

* Logistic Regression
* Binary Classification
* Exploratory Data Analysis
* Feature Scaling
* Train-Test Split
* Confusion Matrix
* Classification Report
* ROC Curve
* AUC Score
* Decision Boundary
* Sigmoid Function

---

## ✅ Conclusion

This practical provides an understanding of **Logistic Regression for binary classification**, including data analysis, feature preprocessing, model training, prediction, visualization, and performance evaluation using standard classification metrics.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# ML Practical 3 – Decision Tree Classification

---

## 📌 Overview

This practical focuses on the implementation of a **Decision Tree Classification** model using the **Iris Dataset** with **Python and Scikit-Learn**.

It covers the complete classification workflow, including **data loading, exploratory data analysis, train-test splitting, model training, prediction, classification metrics, and 5-Fold Cross Validation**.

---

## 🎯 Objectives

* Implement a **Decision Tree Classifier** using Scikit-Learn.
* Work with the **Iris flower dataset**.
* Perform basic **Exploratory Data Analysis (EDA)**.
* Split the dataset into **training and testing sets**.
* Train and predict using a Decision Tree model.
* Evaluate the model using:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
* Apply **5-Fold Cross Validation**.
* Compare model performance using different evaluation metrics.

---

## 📚 Dataset Used

The practical uses the **Iris Dataset** available in Scikit-Learn.

The dataset contains measurements of iris flowers and three target species:

* **Setosa**
* **Versicolor**
* **Virginica**

### Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Target Variable

* Species

---

## 🔄 Project Workflow

The practical follows a complete machine learning classification workflow.

### 1. Data Loading

The Iris dataset is loaded using **Scikit-Learn** and converted into a Pandas DataFrame.

Basic dataset information is explored, including:

* Dataset shape
* Feature names
* Data types
* First few records
* Target class distribution

---

### 2. Exploratory Data Analysis

Basic EDA is performed to understand the dataset.

The practical includes:

* Target class distribution
* Scatter plot
* Box plot
* Feature analysis

A scatter plot is used to visualize the relationship between **Petal Length** and **Petal Width**.

---

### 3. Data Splitting

The dataset is divided into:

**Independent Variables:**

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

**Dependent Variable:**

* Species

The dataset is split into training and testing data using `train_test_split`.

---

### 4. Model Building

A **Decision Tree Classifier** is created using Scikit-Learn.

The model is configured with:

```python
DecisionTreeClassifier(max_depth=3, random_state=42)
```

The model is trained using the training dataset and then used to predict the classes of the test dataset.

---

### 5. Classification Metrics

The performance of the Decision Tree model is evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1 Score**

These metrics help evaluate the classification performance of the model.

---

## 🔄 5-Fold Cross Validation

The practical also implements **5-Fold Cross Validation** using `KFold`.

In 5-Fold Cross Validation:

* The dataset is divided into 5 folds.
* 4 folds are used for training.
* 1 fold is used for testing.
* The process is repeated 5 times.
* The average performance is calculated.

The following metrics are evaluated:

* Accuracy
* Precision
* Recall
* F1 Score

---

## 📊 Model Evaluation

### Accuracy

Accuracy represents the proportion of correctly classified samples out of all samples.

### Precision

Precision measures how many of the samples predicted as a particular class are actually correct.

### Recall

Recall measures how many of the actual samples of a class are correctly identified.

### F1 Score

F1 Score combines **Precision and Recall** into a single metric.

---

## 🛠️ Libraries Used

| **Library**      | **Purpose**                           |
| ---------------- | ------------------------------------- |
| **NumPy**        | Numerical computations                |
| **Pandas**       | Data manipulation and analysis        |
| **Matplotlib**   | Data visualization                    |
| **Scikit-Learn** | Machine learning and model evaluation |

---

## 📂 Project Structure

```text
ML-Practical-3-Decision-Tree-Classification/
│
├── Decision_Tree_Classification.ipynb
├── README.md
│
```

---

## 💻 Requirements

Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## ▶️ Execution

1. Open the Jupyter Notebook.
2. Import the required libraries.
3. Load the Iris dataset.
4. Perform basic Exploratory Data Analysis.
5. Select features and target variable.
6. Split the dataset into training and testing sets.
7. Create and train the Decision Tree Classifier.
8. Generate predictions on the test dataset.
9. Calculate Accuracy, Precision, Recall, and F1 Score.
10. Apply 5-Fold Cross Validation.
11. Calculate the average cross-validation performance.

---

## 📈 Expected Outcomes

After completing this practical, the implementation demonstrates:

* Iris dataset analysis
* Exploratory Data Analysis
* Decision Tree Classification
* Train-Test Split
* Model Prediction
* Accuracy evaluation
* Precision evaluation
* Recall evaluation
* F1 Score evaluation
* 5-Fold Cross Validation

---

## 📝 Conclusion

This practical provides an understanding of **Decision Tree Classification** using the Iris Dataset.

It demonstrates the complete classification workflow, including **data analysis, train-test splitting, model training, prediction, classification metrics, and 5-Fold Cross Validation** using Python and Scikit-Learn.


