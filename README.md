# Calories Burned Prediction

A machine learning regression project developed using **Python** and **Jupyter Notebook** to predict calories burned during gym workout sessions. The project uses gym member workout data, physiological measurements, and workout-related features to build and evaluate predictive models.

## About the Project

The main aim of this project is to develop and evaluate machine learning models that can estimate the number of calories burned during gym workout sessions. Predicting calorie expenditure is useful for fitness tracking, health management, personalized workout planning, and performance monitoring.

The project includes data cleaning, exploratory data analysis, feature engineering, preprocessing, model training, hyperparameter tuning, model evaluation, residual analysis, feature importance analysis, and SHAP explainability.

## Problem Statement

Estimating calories burned during exercise can be difficult because it depends on different factors such as age, gender, weight, height, heart rate, workout duration, workout type, body fat percentage, hydration level, workout frequency, and experience level.

This project solves the problem by using machine learning regression models to learn patterns from workout data and predict calories burned more accurately.

## Dataset Overview

The dataset contains gym member workout session records with physical, physiological, and workout-related information.

The dataset includes **973 records** and **15 columns**.

## Dataset Features

### Input Features

- `Age` - Age of the gym member
- `Gender` - Gender of the gym member
- `Weight (kg)` - Body weight in kilograms
- `Height (m)` - Height in meters
- `Max_BPM` - Maximum heart rate during workout
- `Avg_BPM` - Average heart rate during workout
- `Resting_BPM` - Resting heart rate
- `Session_Duration (hours)` - Workout duration in hours
- `Workout_Type` - Type of workout such as Cardio, Strength, Yoga, or HIIT
- `Fat_Percentage` - Body fat percentage
- `Water_Intake (liters)` - Water intake in liters
- `Workout_Frequency (days/week)` - Number of workout days per week
- `Experience_Level` - Fitness experience level
- `BMI` - Body Mass Index

### Target Variable

- `Calories_Burned` - Number of calories burned during the workout session

## Features of the Project

- Data loading and initial inspection
- Missing value checking
- Duplicate value checking
- Column name cleaning
- Exploratory Data Analysis
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Outlier inspection
- Feature preprocessing
- Encoding categorical variables
- Scaling numerical variables
- Train-test split
- Cross-validation
- Ridge Regression model
- Gradient Boosting Regressor model
- Hyperparameter tuning using GridSearchCV and RandomizedSearchCV
- Model comparison using MAE, RMSE, and R2 Score
- Learning curve analysis
- Residual diagnostics
- Error analysis by calorie bins
- Permutation feature importance
- SHAP explainability

## Machine Learning Models Used

The project trains and evaluates the following regression models:

- Ridge Regression
- Gradient Boosting Regressor

The final model selection is based on performance metrics such as:

- Mean Absolute Error
- Root Mean Squared Error
- R2 Score

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- SHAP

## Author

**Bibek Karki**

## License

This project is created for academic and learning purposes.
