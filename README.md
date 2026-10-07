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



----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# *** ML PRACTICALS ***

# PRACTICAL 4

# ML Practical 4 – K-Nearest Neighbors (KNN) Classification

---

## 📌 Overview

This practical focuses on the implementation of **K-Nearest Neighbors (KNN) Classification** using **Python and Scikit-Learn**.

It covers the complete classification workflow, including **data loading, exploratory data analysis, feature selection, train-test splitting, feature scaling, model training, prediction, accuracy evaluation, visualization, and K value tuning**.

The practical uses the **Social Network Ads dataset** to predict whether a user will purchase a product based on their **Age** and **Estimated Salary**.

---

## 🎯 Objectives

* Implement a **K-Nearest Neighbors (KNN) Classifier** using Scikit-Learn.
* Work with the **Social Network Ads dataset**.
* Perform basic **Exploratory Data Analysis (EDA)**.
* Select appropriate features and target variables.
* Split the dataset into **training and testing sets**.
* Apply **StandardScaler** for feature scaling.
* Train and predict using a **KNN Classification** model.
* Evaluate model performance using **Accuracy**.
* Visualize the KNN classification results.
* Tune the value of **K** to identify the best model performance.

---

## 📚 Dataset Used

The practical uses the **Social Network Ads Dataset**.

The dataset contains information about users and their purchasing behavior.

### Features

* Age
* Estimated Salary

### Target Variable

* Purchased

The `Purchased` variable represents whether the user purchased the product or not.

---

## 🔄 Project Workflow

The practical follows a complete machine learning classification workflow.

### 1. Data Loading

The dataset is loaded using **Pandas** from the `Social_Network_Ads.csv` file.

Basic information about the dataset is explored, including:

* Dataset shape
* First few records
* Target class distribution
* Feature values

---

### 2. Exploratory Data Analysis

Basic EDA is performed to understand the relationship between the input features and target variable.

A **scatter plot** is used to visualize the relationship between:

* Age
* Estimated Salary

The target variable `Purchased` is used to distinguish the different classes in the visualization.

---

### 3. Feature Selection

The following features are selected for model training:

**Input Features:**

* Age
* Estimated Salary

**Target Variable:**

* Purchased

---

### 4. Data Splitting

The dataset is divided into training and testing data using `train_test_split`.

The test size is set to **20%** of the dataset.

The training data is used to train the KNN model, while the testing data is used to evaluate the model.

---

### 5. Feature Scaling

Since KNN is a distance-based algorithm, feature scaling is applied using **StandardScaler**.

The features are standardized so that they have comparable scales.

```python
scaler = StandardScaler()

X_train = scaler.fit_transform(X_train)
X_test = scaler.transform(X_test)
```

---

### 6. Model Building

A **KNeighborsClassifier** is created using Scikit-Learn.

The initial model uses:

```python
KNeighborsClassifier(n_neighbors=5)
```

The model is trained using the scaled training data and then used to predict the classes of the test dataset.

---

### 7. Model Prediction

The trained KNN model is used to generate predictions for the test dataset.

```python
y_pred = knn.predict(X_test)
```

The predicted values are then compared with the actual target values.

---

## 📊 Model Evaluation

The performance of the KNN model is evaluated using **Accuracy Score**.

### Accuracy

Accuracy represents the proportion of correctly classified samples out of all test samples.

```python
accuracy = accuracy_score(y_test, y_pred)
```

The initial KNN model with `K = 5` produces an accuracy of approximately:

```text
Accuracy: 0.7375
```

---

## 📈 K Value Tuning

The value of **K** is an important parameter in KNN classification.

Different K values from **1 to 15** are tested to compare their classification accuracy.

The accuracy values are stored and visualized using a line plot.

The practical identifies the K value that produces the highest accuracy among the tested values.

The observed results include:

| K Value | Accuracy |
| ------- | -------- |
| 1       | 0.725    |
| 2       | 0.713    |
| 3       | 0.775    |
| 4       | 0.762    |
| 5       | 0.738    |
| 6       | 0.750    |
| 7       | 0.750    |
| 8       | 0.762    |
| 9       | 0.738    |
| 10      | 0.750    |
| 11      | 0.775    |
| 12      | 0.800    |
| 13      | 0.775    |
| 14      | 0.800    |
| 15      | 0.775    |

The maximum observed accuracy is:

```text
Best Accuracy: 0.8
```

The first K value achieving this maximum in the practical is:

```text
Best K: 12
```

---

## 🛠️ Libraries Used

| **Library**      | **Purpose**                           |
| ---------------- | ------------------------------------- |
| **Pandas**       | Data manipulation and analysis        |
| **Matplotlib**   | Data visualization                    |
| **Scikit-Learn** | Machine learning and model evaluation |

---

## 📂 Project Structure

```text
ML-Practical-4-KNN-Classification/
│
├── KNN_Classification.ipynb
├── README.md
│
└── dataset/
    └── Social_Network_Ads.csv
```

---

## 💻 Requirements

Install the required Python libraries using:

```text
pip install pandas matplotlib scikit-learn
```

---

## ▶️ Execution

1. Open the Jupyter Notebook.
2. Import the required libraries.
3. Load the Social Network Ads dataset.
4. Perform basic Exploratory Data Analysis.
5. Select features and target variable.
6. Split the dataset into training and testing sets.
7. Apply StandardScaler to scale the input features.
8. Create and train the KNN Classifier.
9. Generate predictions on the test dataset.
10. Calculate the model accuracy.
11. Visualize the KNN classification results.
12. Test different K values from 1 to 15.
13. Plot K values against their corresponding accuracy.
14. Identify the K value with the maximum observed accuracy.

---

## 📈 Expected Outcomes

After completing this practical, the implementation demonstrates:

* Social Network Ads dataset analysis
* Exploratory Data Analysis
* Feature Selection
* Train-Test Split
* Feature Scaling
* K-Nearest Neighbors Classification
* Model Prediction
* Accuracy evaluation
* K Value tuning
* K vs Accuracy visualization
* Selection of the best observed K value

---

## 📝 Conclusion

This practical provides an understanding of **K-Nearest Neighbors (KNN) Classification** using the Social Network Ads Dataset.

It demonstrates the complete classification workflow, including **data analysis, feature selection, train-test splitting, feature scaling, model training, prediction, accuracy evaluation, visualization, and K value tuning** using Python and Scikit-Learn.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**** ML PRACTICALS ****

PRACTICAL 5

ML Practical 5 – Support Vector Machine (SVM) Classification

📌 Overview

This practical focuses on the implementation of Support Vector Machine (SVM) Classification using Python and Scikit-Learn.

It covers the complete SVM workflow, including data loading, exploratory data analysis, feature and target splitting, train-test splitting, model training using Linear, RBF, and Polynomial kernels, model evaluation, and hyperparameter tuning using Grid Search.

The practical uses the Non-linear SVM Dataset to train and compare different SVM models.

🎯 Objectives

Implement a Support Vector Machine (SVM) classifier using Scikit-Learn.

Load and explore the Non-linear SVM Dataset.

Perform basic Exploratory Data Analysis (EDA).

Separate features and target variables.

Split the dataset into training and testing sets.

Train an SVM model using the Linear Kernel.

Train an SVM model using the RBF Kernel.

Train an SVM model using the Polynomial Kernel.

Evaluate model performance using Accuracy.

Tune C and gamma hyperparameters using Grid Search.

Evaluate the best tuned SVM model using Accuracy and Classification Report.

📚 Dataset Used

The practical uses the Non-linear SVM Dataset stored in:

Non_linear_SVM_Dataset.csv

Features

The dataset contains two input features:

X1

X2

Target Variable

Y

The Y variable represents the output/class used for SVM classification.

🔄 Project Workflow

The practical follows a complete machine learning classification workflow.

1. Import Libraries

The following Python libraries are used:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-Learn

2. Load and Preview Dataset

The dataset is loaded using Pandas from the Non_linear_SVM_Dataset.csv file.

The dataset structure is checked using:

df.info()

This helps understand the columns and data types present in the dataset.

3. Feature and Target Splitting

The dataset is divided into input features and target variable.

Input Features:

X1

X2

Target Variable:

Y

The target column Y is separated from the input features.

4. Exploratory Data Analysis & Visualization

Basic visualization is performed to understand the relationship between the features and target.

The practical includes:

2D Scatter Plot

3D Scatter Plot

The scatter plots visualize the relationship between X1, X2, and Y.

5. Train-Test Split

The dataset is divided into training and testing data using train_test_split.

The test size is set to 30% of the dataset.

X_train, X_test, y_train, y_test = train_test_split(
    X, Y, test_size=0.3, random_state=42
)

The training data is used to train the SVM models, while the testing data is used to evaluate their performance.

🤖 SVM Model Training

6. Linear Kernel

A Support Vector Machine model is created using the Linear Kernel.

linear_svm = SVC(kernel='linear')

The model is trained using the training dataset and predictions are generated for the test dataset.

The model performance is evaluated using Accuracy Score.

7. RBF Kernel

An SVM model is created using the RBF (Radial Basis Function) Kernel.

rbf_svm = SVC(kernel='rbf', C=10, gamma='scale')

The RBF kernel is used to handle non-linear relationships in the dataset.

The trained model is used to make predictions and calculate accuracy.

8. Polynomial Kernel

An SVM model is created using the Polynomial Kernel.

poly_svm = SVC(kernel='poly', C=10, degree=2)

The Polynomial Kernel is used to model non-linear relationships using polynomial transformations.

The model is trained and evaluated using the test dataset.

📊 Model Evaluation

The SVM models are evaluated using Accuracy Score.

Accuracy

Accuracy represents the proportion of correctly classified samples out of all test samples.

accuracy_score(y_test, y_pred)

The accuracy is calculated separately for:

Linear SVM

RBF SVM

Polynomial SVM

This allows the performance of different kernels to be compared.

🔧 Hyperparameter Tuning via Grid Search

The practical uses GridSearchCV to find suitable values of the SVM hyperparameters C and gamma for the RBF kernel.

The parameters tested are:

params = {
    'C': [0.1, 1, 10, 100],
    'gamma': ['scale', 0.01, 0.1, 1]
}

The Grid Search uses:

RBF Kernel

5-Fold Cross Validation

Accuracy as the scoring metric

The best parameter combination is obtained using:

grid.best_params_

📈 Evaluate Best Tuned Model

After Grid Search, the best SVM model is selected using:

best_model = grid.best_estimator_

The best model is then used to make predictions on the test dataset.

The final tuned model is evaluated using:

Accuracy

Classification Report

The classification report provides detailed classification performance for the model.

📚 Key Concepts

Support Vector Machine (SVM)

Classification

Linear Kernel

RBF Kernel

Polynomial Kernel

C Hyperparameter

Gamma Hyperparameter

Grid Search

GridSearchCV

Train-Test Split

5-Fold Cross Validation

Accuracy Score

Classification Report

Exploratory Data Analysis

🛠️ Libraries Used

Library

Purpose

NumPy

Numerical computations

Pandas

Data loading and manipulation

Matplotlib

Data visualization

Seaborn

Data visualization

Scikit-Learn

SVM model, model evaluation, train-test split, and hyperparameter tuning

📂 Project Structure

ML-Practical-5-SVM-Classification/
│
├── ML_PRACTICAL_5.ipynb
├── README.md
│
└── dataset/
    └── Non_linear_SVM_Dataset.csv

💻 Requirements

Install the required Python libraries using:

pip install numpy pandas matplotlib seaborn scikit-learn

▶️ Execution

Open the Jupyter Notebook.

Import the required libraries.

Load the Non_linear_SVM_Dataset.csv dataset.

Preview and inspect the dataset.

Separate features and target variable.

Perform Exploratory Data Analysis.

Visualize the dataset using 2D and 3D scatter plots.

Split the dataset into training and testing sets.

Create and train the Linear SVM model.

Calculate Linear SVM accuracy.

Create and train the RBF SVM model.

Calculate RBF SVM accuracy.

Create and train the Polynomial SVM model.

Calculate Polynomial SVM accuracy.

Apply Grid Search for tuning C and gamma.

Find the best hyperparameters.

Evaluate the best tuned RBF SVM model.

Display the Classification Report.

📈 Expected Outcomes

After completing this practical, the implementation demonstrates:

Non-linear SVM dataset analysis

Exploratory Data Analysis

Feature and target selection

Train-Test Split

Linear Kernel SVM

RBF Kernel SVM

Polynomial Kernel SVM

Accuracy evaluation

Hyperparameter tuning

Grid Search

5-Fold Cross Validation

Best parameter selection

Classification Report

📝 Conclusion

This practical provides an understanding of Support Vector Machine (SVM) Classification using the Non-linear SVM Dataset.

It demonstrates the complete classification workflow, including data analysis, feature selection, train-test splitting, Linear, RBF and Polynomial kernel models, accuracy evaluation, hyperparameter tuning using Grid Search, and evaluation of the best tuned model using Python and Scikit-Learn.

