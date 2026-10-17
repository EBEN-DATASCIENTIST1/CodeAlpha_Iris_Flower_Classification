# Iris Flower Classification

## Project Overview

This project uses machine learning to classify Iris flowers into three species: **Iris-setosa, Iris-versicolor, and Iris-virginica**. It uses flower measurements to train and evaluate multiple classification algorithms.

This project was completed as part of the CodeAlpha Data Science Internship.

## Objectives

- Explore and visualize the Iris dataset.
- Prepare the data for machine learning.
- Train and compare classification models.
- Evaluate model performance using classification metrics.
- Predict the species of a new Iris flower.

## Dataset

The dataset contains 150 observations and the following columns:

- `SepalLengthCm`
- `SepalWidthCm`
- `PetalLengthCm`
- `PetalWidthCm`
- `Species`

The `Id` column is an identifier and is not used as a predictive feature. The dataset contains 50 observations for each species and no missing values.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

1. Load the Iris dataset using Pandas.
2. Explore the data using statistical summaries and visualizations.
3. Separate the four numerical features from the target species.
4. Split the dataset into 80% training data and 20% testing data using stratified sampling.
5. Apply `StandardScaler` to the training and test features.
6. Train Logistic Regression, K-Nearest Neighbors, Decision Tree, Support Vector Classifier, and Random Forest models.
7. Evaluate the models using accuracy, precision, recall, and F1-score.
8. Use the best-performing model to predict the species of a new flower.

## Model Performance

| Model                     |   Accuracy |  Precision |     Recall |   F1-Score |
| ------------------------- | ---------: | ---------: | ---------: | ---------: |
| Logistic Regression       |     93.33% |     93.33% |     93.33% |     93.33% |
| K-Nearest Neighbors       |     93.33% |     94.44% |     93.33% |     93.27% |
| Decision Tree             |     90.00% |     90.24% |     90.00% |     89.97% |
| Support Vector Classifier | **96.67%** | **96.97%** | **96.67%** | **96.66%** |
| Random Forest             |     90.00% |     90.24% |     90.00% |     89.97% |

The Support Vector Classifier achieved the highest accuracy on the test set, correctly classifying 29 out of 30 flowers.

## Sample Prediction

A flower with the following measurements was used for a sample prediction:

- Sepal length: 5.1 cm
- Sepal width: 3.5 cm
- Petal length: 1.4 cm
- Petal width: 0.2 cm

**Predicted species:** `Iris-setosa`

## Results

The model comparison results are saved in `results/model_comparison.csv`. The notebook also includes exploratory visualizations and a confusion matrix for the selected model.

## Conclusion

This project demonstrates how machine learning classification algorithms can identify Iris flower species from numerical measurements. The Support Vector Classifier achieved the best test-set performance among the five evaluated models.

## Author

**EBENEZER DABIRE**

GitHub: https://github.com/EBEN-DATASCIENTIST1
