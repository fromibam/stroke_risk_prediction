# stroke_risk_prediction
Predicting stroke risk using K-nearest Neighbors classification model from patient health data - 91.5% accuracy

## Overview
A machine learning classification project that predicts whether a patient is at risk of stroke based on their health data.

## Problem Statement
Stroke is one of the leading causes of death and disability worldwide, yet early detection remains a challenge for medical professionals. Delayed diagnosis can result in severe, irreversible damage or death. This project builds a machine learning classification model using K-Nearest Neighbors (KNN) to predict a patient's stroke risk based on their health data, supporting doctors in making faster and more informed decisions.

## Dataset
- Source: [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?datasetld=1120859)
- Target variable: stroke (0 = No Risk, 1 = At Risk)

## Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy, Scikit-learn

## Methodology
1. Data Preprocessing & Cleaning
   - Handled missing values
   - Binning data
   - Encoded categorical data
2. Exploratory Data Analysis (EDA)
3. Model Implementation — K-Nearest Neighbors (KNN)
4. Model Evaluation

## Results
|  Metric  |  Score  |
|----------|---------|
| Accuracy |  91.5%  |

## How to Run
1. Download the dataset from the Kaggle link above
2. Open `Stroke_Risk_Prediction.ipynb` in Google Colab
3. Update the file path to match where you saved the dataset
4. Run all cells
