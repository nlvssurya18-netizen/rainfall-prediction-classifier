# Rainfall Prediction Using Machine Learning

## 1. Project Overview

Rainfall Prediction is a Machine Learning classification project
that predicts whether it will rain the following day based on
historical weather observations.

The project uses the Australian Weather Dataset (weatherAUS).

The target variable is RainTomorrow, which contains two classes:

- Yes: Rain is expected tomorrow.
- No: Rain is not expected tomorrow.

## 2. Objectives

- Analyze historical weather data.
- Perform data cleaning and preprocessing.
- Handle missing values.
- Identify important weather patterns.
- Train multiple Machine Learning models.
- Compare model performance.
- Predict the possibility of rainfall.

## 3. Dataset Description

Dataset: Australian Weather Dataset (weatherAUS)

Number of records: 145,460

Number of columns: 23

Important features:

- MinTemp
- MaxTemp
- Rainfall
- Evaporation
- Sunshine
- WindGustSpeed
- Humidity9am
- Humidity3pm
- Pressure9am
- Pressure3pm
- Cloud9am
- Cloud3pm
- RainToday
- RainTomorrow

Target variable: RainTomorrow

## 4. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 5. Machine Learning Algorithms

The following classification algorithms are implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Extra Trees Classifier

## 6. Project Workflow

1. Dataset Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Handling Missing Values
6. Categorical Feature Encoding
7. Feature Scaling
8. Train-Test Splitting
9. Model Training
10. Model Evaluation
11. Model Comparison
12. Rainfall Prediction

## 7. Model Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

ROC-AUC is also used to select the best-performing model.

## 8. Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

## 9. How to Run

Place the dataset and Python file in the same folder.

Run:

```bash
python rainfall_prediction.py
```

## 10. Output

The project generates:

- Rainfall distribution graph
- Weather correlation heatmap
- Confusion matrices
- ROC curve comparison
- Model comparison CSV
- Trained best-performing model
- Sample rainfall prediction

All generated outputs are stored in the outputs folder.

## 11. Expected Outcome

The system identifies weather patterns from historical
observations and predicts whether rainfall is expected
on the following day.

The performance of multiple Machine Learning algorithms
is compared to identify the most suitable model.

## 12. Conclusion

This project demonstrates how Machine Learning can be
used for weather forecasting through historical weather
data analysis and classification algorithms.

It provides a comparative study of different algorithms
and helps understand the role of data preprocessing,
feature engineering, and model evaluation in prediction.
