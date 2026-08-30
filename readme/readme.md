# Student Performance Prediction

## Overview

This project uses Machine Learning to predict a student's final exam score based on study hours, attendance, previous score, and sleep hours.

A Linear Regression model is trained and evaluated using a synthetic dataset.

## Objective

The objective of this project is to understand and implement a complete machine learning workflow:

- Data generation
- Data analysis
- Exploratory Data Analysis
- Data visualization
- Feature selection
- Train-test split
- Linear Regression
- Model evaluation
- Prediction
- Model saving and loading

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Joblib
- JupyterLab

## Dataset

The project uses a synthetic dataset containing 500 student records.

### Features

- Hours_Studied
- Attendance
- Previous_Score
- Sleep_Hours

### Target

- Final_Score

## Machine Learning Model

Linear Regression is used to predict the final score.

The dataset is divided into:

- 80% training data
- 20% testing data

## Model Performance

The model achieved the following results on the test set:

| Metric | Score |
|---|---:|
| MAE | 4.29 |
| MSE | 27.13 |
| RMSE | 5.21 |
| R² Score | 0.85 |

## Sample Prediction

The trained model was used to predict the final score for a sample student using:

- Hours Studied: 7
- Attendance: 85
- Previous Score: 72
- Sleep Hours: 7

Predicted Final Score: 87.61

## Project Structure

student-performance-prediction/

├── data/

├── models/

├── notebooks/

├── README.md

└── .gitignore

## Limitations

The dataset used in this project is synthetic and was created for learning and demonstration purposes. Therefore, the model performance should not be interpreted as real-world student performance prediction.

## Future Improvements

- Use a real-world student performance dataset
- Compare multiple regression models
- Perform feature engineering
- Build an interactive prediction interface
- Deploy the model as a web application