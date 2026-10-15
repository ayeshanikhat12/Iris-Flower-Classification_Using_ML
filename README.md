# Iris Flower Classification Using Machine Learning 🌸
![Uploading Iris Flower Species .png…]()



## Project Overview

Iris Flower Classification is a machine learning project that predicts the species of an iris flower based on its sepal and petal measurements. This project explores the dataset, visualizes flower measurements, compares multiple machine learning algorithms, and tunes a Random Forest model to make predictions.

## Problem Statement

Identifying iris flower species using measurements can be approached as a classification problem. The goal is to build a machine learning model that predicts the correct species from the given flower measurements.

## Objective

- Understand and explore the Iris dataset.
- Perform data inspection and cleaning.
- Visualize relationships between flower measurements.
- Train and compare seven machine learning models.
- Improve the Random Forest model using hyperparameter tuning.
- Predict the species of a new iris flower.

## Project Details

**Project Name:** Iris Flower Classification Using ML

**Project Type:** Machine Learning — Classification

**Tools and Technologies:**
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Dataset Description

The dataset was obtained from the UCI Machine Learning Repository's Iris dataset.

It contains four numerical features and one target column:

| Column | Description |
|---|---|
| `sepal_length` | Length of the sepal |
| `sepal_width` | Width of the sepal |
| `petal_length` | Length of the petal |
| `petal_width` | Width of the petal |
| `species` | Iris flower species |

The dataset contains three species: Iris-setosa, Iris-versicolor, and Iris-virginica.

During data preparation, missing rows were removed and duplicate records were checked and removed. The final dataset used for the project contained 147 rows and 5 columns.

## Project Workflow

1. Load and inspect the dataset.
2. Check data types, missing values, and duplicate records.
3. Perform exploratory data analysis.
4. Create histograms, scatter plots, and a correlation heatmap.
5. Encode the target species into numerical labels.
6. Split the data into training and testing sets.
7. Train and compare machine learning models.
8. Tune the Random Forest model using GridSearchCV.
9. Evaluate the tuned model and predict a new flower's species.

## Machine Learning Models

The following seven classification algorithms were compared:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. K-Nearest Neighbors (KNN)
5. Linear Discriminant Analysis (LDA)
6. Gaussian Naive Bayes
7. Support Vector Classifier (SVC)

## Hyperparameter Tuning

GridSearchCV with 5-fold cross-validation was used to tune the Random Forest model.

**Best Parameters:**

- `max_depth`: None
- `min_samples_leaf`: 2
- `min_samples_split`: 2
- `n_estimators`: 50

## Results

The tuned Random Forest model achieved the following test result:

| Metric | Result |
|---|---:|
| Final Model | Random Forest |
| Test Accuracy | 91.11% |

The model was also used to predict the species of a new flower using its sepal and petal measurements.

**Sample Prediction:** `Iris-setosa`

## Conclusion

This project demonstrates the use of machine learning for iris flower classification. The dataset was explored and cleaned, visualizations were created, and seven classification models were compared. The Random Forest model was tuned using GridSearchCV and achieved a test accuracy of 91.11%.

The project provided practical experience with data preprocessing, exploratory data analysis, classification algorithms, model evaluation, and hyperparameter tuning.

## Dataset Reference

UCI Machine Learning Repository — Iris Dataset:

https://archive.ics.uci.edu/dataset/53/iris
