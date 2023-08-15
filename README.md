# Software Defect Prediction Project

<!--![Project Image](project_image.jpg) <!-- Replace with an image representing your project -->

## Table of Contents

- [About](#about)
- [Motivation](#motivation)
- [Features](#features)
- [Datasets](#datasets)
- [Machine Learning Algorithms](#machine-learning-algorithms)
- [Evaluation Metrics](#evaluation-metrics)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## About

This repository contains the source code and resources for my software defect prediction project. The project aims to explore the application of machine learning algorithms for early identification of software defects, enhancing software quality and reducing maintenance costs.

## Motivation

Software defects can have significant implications on software quality, user satisfaction, and maintenance efforts. This project was motivated by the desire to leverage machine learning techniques to predict defects more accurately, aiding software developers in proactively addressing potential issues.

## Features

- Comparative analysis of 10 machine learning algorithms
- Addressing class imbalance using Random Over-Sampling (ROS)
- Evaluation using metrics such as accuracy, precision, recall, AUC-ROC
- Cross-validation with 10 splits using RepeatedStratifiedKFold

## Datasets

The project utilizes 7 publicly available datasets:
- CM1
- JM1
- KC1
- KC2
- MC1
- MW1
- PC1

## Machine Learning Algorithms

The following algorithms are evaluated in this project:
- Logistic Regression
- XGBoost
- AdaBoost
- Voting Classifier
- Random Forest
- Decision Tree
- SVM
- Gradient Boosting
- KNN
- Bagging Classifier

## Evaluation Metrics

The project employs various evaluation metrics:
- Prediction Accuracy
- Precision
- Recall
- AUC-ROC

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/software-defect-prediction.git
   ```
2. Install Dependencies
   ``` pip install -r requirements.txt ```
3. Open each folder to access the main.ipynb fiels

