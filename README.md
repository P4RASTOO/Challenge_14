<img width="759" alt="Screenshot 2023-08-16 at 12 08 04 PM" src="https://github.com/P4RASTOO/Challenge_14/assets/132952512/c595424e-ee96-4e22-be68-5a7236a9d52b">

# Challenge_14 Report

## Overview of the Analysis
The purpose of this analysis is to enhance the existing algorithmic trading systems by incorporating machine learning algorithms that can adapt to new data. The goal is to improve the firm's competitive advantage in asset management and trading by accurately predicting asset price movements.

### Financial Information and Prediction Task:

The data consists of two simple moving averages (SMAs) labeled as "SMA_Fast" and "SMA_Slow," which are time series representations of asset price trends. The aim is to predict whether the asset price will increase (1) or decrease (-1) based on the relationship between these two moving averages.
Variables and Exploration:
The target variable to predict is the direction of the asset price movement, represented by 1 (increase) or -1 (decrease). The data exploration may involve calculating the value counts of the target variable to understand the class distribution.

### Stages of the Machine Learning Process:

1) Data Preprocessing: The provided data is likely preprocessed, scaled, and split into training and testing sets.
2) Model Selection and Training: Support Vector Machine (SVM) and Logistic Regression (LR) models are chosen and trained on the training data.
3) Model Evaluation: The trained models are evaluated using the testing data to calculate precision, recall, and other classification metrics.


## Results
Here are the balanced accuracy scores and precision-recall scores for the machine learning models:

SVM Model:

* Balanced Accuracy Score: 0.50
* Precision for -1 (decrease): 0.43
* Precision for 1 (increase): 0.56
* Recall for -1 (decrease): 0.04
* Recall for 1 (increase): 0.96


Logistic Regression (LR) Model:

* Balanced Accuracy Score: 0.50
* Precision for -1 (decrease): 0.44
* Precision for 1 (increase): 0.56
* Recall for -1 (decrease): 0.33
* Recall for 1 (increase): 0.66

## Summary

Based on the results, both models have similar balanced accuracy scores and precision-recall scores. The SVM model has a slightly higher recall for the 1 class (increase), while the LR model has a slightly higher recall for the -1 class (decrease).

Given the similar performance, it's recommended to consider other factors such as model complexity, interpretability, and ease of implementation when deciding on the final model. Additionally, further analysis could explore ensemble methods or fine-tuning hyperparameters to potentially improve model performance. Ultimately, the choice of model may depend on the specific trading strategy and risk tolerance of the firm.
