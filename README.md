# _health_insurance_prediction
Health Insurance Prediction Project - ML(Regression)

#### Overview:
This project is focused on predicting health insurance premiums using a dataset of approximately 50,000 records. It was built as a part of a data science project using Streamlit and deployed for public access. The model leverages several machine learning techniques to provide accurate predictions based on user inputs such as age, gender, medical history, and other factors.

#### Features:
* Data Profiling & Cleaning: Initial exploration and cleaning were done to handle missing values and outliers.
* Feature Engineering: Key features such as BMI category, income level, and employment status were derived to enhance model performance.
* Modeling Techniques:
  * Linear Regression
  * Ridge Regression
  * XGBRegressor (provided the best performance)
* Hyperparameter Tuning: Used RandomizedSearchCV and GridSearchCV to find optimal model parameters.
* Streamlit Web App: Provides an interactive UI for users to input personal information and predict their health insurance premium in real time.

#### Project Files:
* main.py: Contains the Streamlit application code, handling the UI and model integration.
* prediction_helper.py: Helper functions used to preprocess data and make predictions.
