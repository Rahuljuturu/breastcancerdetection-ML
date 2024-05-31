# breastcancerdetection-ML

# Breast Cancer Prediction Project

## Project Description

This project aims to predict breast cancer using data from cell nuclei features. We use the Wisconsin Diagnostic Breast Cancer (WDBC) dataset, which contains measurements from breast cancer cells.

## Features

- **Data Preprocessing**: Cleaning and preparing the data for analysis.
- **Exploratory Data Analysis (EDA)**: Understanding the data using graphs and statistics.
- **Feature Engineering**: Modifying or creating features to improve model performance.
- **Model Building**: Creating machine learning models to predict breast cancer.
- **Model Evaluation**: Assessing how well the models perform.

## Dataset

The dataset has 569 entries and 31 features, including:

- `radius_mean`, `texture_mean`, etc.: Average values of cell characteristics.
- `radius_se`, `texture_se`, etc.: Standard errors of the cell characteristics.
- `radius_worst`, `texture_worst`, etc.: Worst values of the cell characteristics.
- `diagnosis`: The cancer diagnosis (M = malignant, B = benign).

## Data Preprocessing

1. **Removing Unnecessary Columns**: Dropping columns like `id` that are not needed.
2. **Encoding Categorical Data**: Changing `diagnosis` from M/B to 1/0 for model training.
3. **Feature Scaling**: Standardizing feature values to the same scale.

## Exploratory Data Analysis (EDA)

- **Visualizing Distribution**: Plotting the spread and central values of features.
- **Correlation Analysis**: Checking relationships between features and the diagnosis.
- **Pair Plots**: Visualizing relationships between pairs of features and the diagnosis.

## Model Building

1. **Logistic Regression**: Simple and easy-to-interpret model for binary classification.
2. **Decision Trees**: Captures non-linear relationships.
3. **Random Forest**: Combines multiple decision trees for better performance.
4. **Support Vector Machine (SVM)**: Powerful model for binary classification.
5. **K-Nearest Neighbors (KNN)**: Classifies based on proximity to other data points.

## Model Evaluation

- **Accuracy**: The ratio of correct predictions to total predictions.
- **Confusion Matrix**: Summarizes prediction results.
- **Precision, Recall, and F1 Score**: Metrics to evaluate prediction quality.
- **ROC Curve and AUC**: Visual and quantitative assessment of model performance.


## Conclusion

This project shows how to use data preprocessing, exploratory data analysis, feature engineering, and machine learning to predict breast cancer. These models can help in early detection and treatment planning.



Feel free to adjust this description to better fit your project.
