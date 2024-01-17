# Online News Popularity Prediction

## Overview

This project focuses on predicting the popularity of online news articles using various machine learning classification models. The analysis includes data exploration, model training, classification, and model evaluation.

## Data Exploration

The data exploration section involves importing necessary libraries, loading the dataset, and performing basic exploratory data analysis. Key steps include:

- Importing libraries: NumPy, Pandas, Matplotlib, Seaborn, and others.
- Loading the dataset from Google Drive.
- Checking the structure of the dataset, handling duplicates, and exploring summary statistics.
- Exploring features, visualizing data distributions, and identifying patterns.

## Model Training

The model training section involves preparing the dataset, splitting it into training and testing sets, and training various classification models. Key steps include:

- Importing necessary libraries for model training.
- Defining classification models: KNeighborsClassifier, RandomForestClassifier, AdaBoostClassifier, GaussianNB, LogisticRegression, SVC, DecisionTreeClassifier, BaggingClassifier, and SGDClassifier.
- Splitting the dataset into training and testing sets.

## Classification Model

In this section, several classification models are applied to predict the popularity of online news articles. Key models include:

- AdaBoostClassifier
- LogisticRegression
- RandomForestClassifier
- GaussianNB
- SVC
- KNeighborsClassifier
- BaggingClassifier
- DecisionTreeClassifier
- SGDClassifier

## Model Evaluation

Model evaluation involves assessing the performance of each classification model using various metrics. Key steps include:

- Training models on different subsets of the dataset (1%, 10%, 100%).
- Calculating metrics such as accuracy, F1 score, and AUC for both training and testing sets.
- Visualizing the performance metrics using bar plots.

## Instructions for Running the Code

1. Import the required libraries by running the initial code cells.
2. Load the dataset from Google Drive.
3. Follow the step-by-step instructions provided in the  notebook for data exploration, model training, and evaluation.
4. Execute the provided code cells for each step.
