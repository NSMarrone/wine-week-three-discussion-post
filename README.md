# Wine Classification Project
A beginner-friendly machine learning project that predicts wine types using Python and scikit-learn.

## What This Project Does
Goal: Predict which of 3 wine cultivars a sample belongs to based on 13 chemical properties.   Models Used: Logistic Regression and Random Forest.

## Steps in the Notebook
Load Libraries: Import pandas, numpy, matplotlib, and scikit-learn.
Load Data: Get the Wine dataset built into scikit-learn.
Explore Data: Check summary stats and class distribution.
Split Data: Divide data into 80% training and 20% testing sets.
Train Logistic Regression: Scale the features and train a baseline model.
Evaluate Model: Check accuracy, precision, recall, and view a confusion matrix.
Train Random Forest: Train a tree-based model for comparison.
Compare Results: See which model performed better.
Test Single Sample: Make a prediction on a single test wine sample.

## How to Run
Install the required libraries:
pip install numpy pandas matplotlib seaborn scikit-learn

Open Jupyter Notebook and run the cells from top to bottom.

## Insights & Summary
Models were evaluated using accuracy scores, classification reports (precision, recall, and F1-score), and confusion matrices.
Because the dataset is small and clean, the reported metrics on a single train/test split serve only as an initial estimate and may be incorrect compared to real life performance.
The analysis suggests that utilizing stratified cross-validation and hyperparameter tuning would provide a more consistent model comparison.   
