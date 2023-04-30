# Text Classification on Consumer Complaint Dataset
This repository contains code for performing a text classification task on the Consumer Complaint Dataset available on [Data.gov](https://catalog.data.gov/dataset/consumer-complaint-database). The objective is to classify the complaints into four categories, namely:

1. Credit reporting, repair, or other
2. Debt collection
3. Consumer Loan
4. Mortgage

The following steps were followed for this task:

## 1. Explanatory Data Analysis and Feature Engineering
Exploratory data analysis (EDA) was performed on the dataset to understand its distribution and characteristics. Feature engineering techniques such as creating new features based on existing ones, handling missing values, and outlier detection were also applied.

## 2. Text Pre-Processing
The complaint text was pre-processed to remove noise, stop words, and perform stemming/lemmatization. This step also involved converting the text into a numerical format suitable for machine learning models.

## 3. Selection of Multi Classification model
Several machine learning models such as Logistic Regression, Random Forest, Naive Bayes, and Support Vector Machines (SVM) were trained on the pre-processed data to select the best-performing model.

## 4. Comparison of model performance
The performance of each model was compared using evaluation metrics such as accuracy, precision, recall, and F1-score.

## 5. Model Evaluation
The best model was evaluated on a hold-out test set to estimate its generalization performance.

## 6. Prediction
The final model was used to make predictions on new, unseen complaints.

## Requirements
* Python 3
* scikit-learn
* pandas
* numpy
* nltk

## Usage
Download the dataset from [Data.gov](https://catalog.data.gov/dataset/consumer-complaint-database)
Run the notebook text_classification.ipynb to perform the text classification task.
