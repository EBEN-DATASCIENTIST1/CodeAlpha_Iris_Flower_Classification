# Iris Flower Classification

## Project Overview

This project was completed as part of the CodeAlpha Data Science Internship.

The objective is to build a machine-learning classification model that can
predict the species of an Iris flower from its sepal and petal measurements.

The Iris dataset contains three species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Dataset

The dataset contains 150 flower samples and four measurement features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The `Id` column is used only as an identifier and is not used for prediction.

## Exploratory Data Analysis

The dataset was explored using:

- Dataset information
- Descriptive statistics
- Missing-value analysis
- Species distribution
- Pairplot
- Feature boxplots

## Machine Learning Models

The following classification algorithms were trained and compared:

1. Logistic Regression
2. K-Nearest Neighbors
3. Decision Tree
4. Support Vector Machine
5. Random Forest

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Results

| Model                  | Accuracy | Precision | Recall | F1 Score |
| ---------------------- | -------: | --------: | -----: | -------: |
| Logistic Regression    |   93.33% |    93.33% | 93.33% |   93.33% |
| K-Nearest Neighbors    |   93.33% |    94.44% | 93.33% |   93.27% |
| Decision Tree          |   90.00% |    90.24% | 90.00% |   89.97% |
| Support Vector Machine |   96.67% |    96.97% | 96.67% |   96.66% |
| Random Forest          |   90.00% |    90.24% | 90.00% |   89.97% |

The Support Vector Machine had the highest observed performance on the
20% test split, with an accuracy of 96.67%.

## Prediction Example

A new flower with the following measurements was tested:

- Sepal Length: 5.1 cm
- Sepal Width: 3.5 cm
- Petal Length: 1.4 cm
- Petal Width: 0.2 cm

Predicted species:

**Iris-setosa**

## Project Structure

text
CodeAlpha_Iris_Flower_Classification/
│
├── data/
│ └── Iris.csv
│
├── notebooks/
│ └── iris_classification.ipynb
│
├── results/
│ └── model_comparison.csv
│
├── README.md
└── requirements.txt
