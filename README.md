Breast Cancer Classification using Logistic Regression

Project Overview

This is a beginner machine learning classification project using the Breast Cancer Wisconsin dataset available through Scikit-learn.

The objective is to build a machine learning model that classifies tumours into two categories: malignant and benign.

Dataset

Source: Scikit-learn built-in Breast Cancer Wisconsin dataset

Number of samples: 569

Number of features: 30

Target classes:

0 — Malignant

1 — Benign

Tools and Technologies

Python

Google Colab

NumPy

pandas

Scikit-learn

Workflow

Loaded and explored the dataset.

Examined the dataset structure and features.

Split the data into training and test sets using stratified sampling.

Built a Scikit-learn Pipeline with StandardScaler and Logistic Regression.

Evaluated the model using classification metrics.

Examined the confusion matrix, precision, recall and F1-score.

Studied predicted probabilities and classification thresholds.

Evaluated discrimination using ROC-AUC and Precision–Recall analysis.

Used stratified 5-fold cross-validation.

Applied GridSearchCV to tune the Logistic Regression hyperparameter C.

Model Selection and Results

The selected hyperparameter was:

C = 1

Evaluation results:

Metric

Result

Best mean cross-validation ROC-AUC

0.99587

Held-out test ROC-AUC

0.99537

The cross-validation and held-out test ROC-AUC scores were very close in this experiment.

Key Learning Outcomes

Through this project, I practised:

Building a classification pipeline

Applying feature scaling without data leakage

Understanding confusion matrices and classification metrics

Evaluating model performance using ROC-AUC

Understanding classification thresholds

Performing stratified cross-validation

Tuning hyperparameters using GridSearchCV

How to Run

Open the notebook in Google Colab.

Run the cells sequentially.

The dataset is loaded directly from Scikit-learn, so no separate dataset download is required.

Project Context

This is a personal machine learning learning project developed as part of my transition into Machine Learning Engineering.

The project is intended for educational purposes and is not a clinically validated diagnostic system.
