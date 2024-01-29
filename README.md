# ChurnGuard: Predicting Customer Churn in Banking with Binary Classification

## Overview

ChurnGuard is a predictive modeling project focused on binary classification to foresee customer churn in the banking sector. The primary objective is to develop a model that can effectively identify customers likely to churn. The implementation utilizes machine learning techniques, specifically the XGBoost algorithm, to achieve this predictive task.

## Key Features

- **Feature Engineering:** The project employs creative feature engineering techniques, such as creating new features based on existing ones. These features include transformations of age, tenure, balance, and other variables to enhance the model's predictive power.

- **Data Preprocessing:** The dataset is preprocessed to handle categorical variables through one-hot encoding. Additionally, data is split into training and validation sets for model evaluation.

- **XGBoost Model:** The XGBoost classifier is utilized for its ability to handle complex relationships within the data. The model is fine-tuned using hyperparameters obtained through a combination of randomized search and grid search.

- **Model Evaluation:** The trained XGBoost model is evaluated using ROC AUC scores on both the training and validation sets, providing insights into its predictive performance.

- **Submission File:** Predictions on the test set are stored in a CSV file named `submission.csv`, including customer IDs and the corresponding churn probabilities.

- **ROC Curve Visualization:** The ROC curve is plotted to visualize the trade-off between true positive rate and false positive rate, providing a comprehensive understanding of the model's performance.

## Project Structure

- **ChurnGuard.ipynb:** Jupyter Notebook containing the main project code, including data loading, preprocessing, feature engineering, model building, training, evaluation, and result visualization.

- **train.csv and test.csv:** Datasets used for training and testing the XGBoost model.

- **submission.csv:** CSV file containing the predicted probabilities of customer churn for the test set.

- **requirements.txt:** File listing the project dependencies, including pandas, xgboost, scikit-learn, matplotlib, seaborn, and other necessary libraries.

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/NabilYimer/ChurnGuard-Predicting-Customer-Churn-in-Banking-with-Binary-Classification
2. **Install the required dependencies:**

  ```bash
   pip install -r requirements.txt
