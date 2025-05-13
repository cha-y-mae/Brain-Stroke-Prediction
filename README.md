# Brain Stroke Prediction - Machine Learning Project

This repository contains a machine learning pipeline to predict the risk of brain stroke based on patient health metrics. The goal is to help identify high-risk individuals using classification models trained on real-world data.

## 📁 Project Structure

- `ML_project.ipynb`: Main Jupyter notebook with data analysis, preprocessing, model training, and evaluation.
- `README.md`: Project overview and setup instructions.

## Dataset

The dataset used in this project is from [Kaggle - Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset), which includes patient information such as age, gender, hypertension status, heart disease, and more.

## Features

- Exploratory Data Analysis (EDA)
- Handling missing values
- Encoding categorical variables
- Balancing dataset using SMOTE
- Training models:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Neural Networks (MLPClassifier)
- Performance evaluation using:
  - Accuracy
  - F1 Score
  - AUC (Area Under Curve)
- Confusion matrix and ROC curves

## Requirements

To run this project, you need Python and the following libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn
