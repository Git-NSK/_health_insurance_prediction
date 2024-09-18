# _health_insurance_prediction
Health Insurance Prediction Project - ML(Regression)

#### Overview:
This project is focused on predicting health insurance premiums using a dataset of approximately 50,000 records. It was built as a part of a data science project using Streamlit and deployed for public access. The model leverages several machine learning techniques to provide accurate predictions based on user inputs such as age, gender, medical history, and other factors.

#### Features:
* Data Profiling & Cleaning: Initial exploration and cleaning were done to handle missing values and outliers.
* Feature Engineering: Key features such as risk_score, income level, and smoking habits were derived to enhance model performance.
* Modeling Techniques:
  * Linear Regression
  * Ridge Regression
  * XGBRegressor (provided the best performance)
* Hyperparameter Tuning: Used RandomizedSearchCV to find optimal model parameters.
* Streamlit Web App: Provides an interactive UI for users to input personal information and predict their health insurance premium in real time.

#### Project Files:
* Shield_insurance_premium_older_with_gr.ipynb : This notebook analyzes insurance premiums for older age groups(age > 25), exploring factors that influence premium rates based on demographic data.
* Shield_insurance_premium_younger_with_gr.ipynb : This notebook analyzes insurance premiums for older age groups(age <= 25), exploring factors that influence premium rates based on demographic data.
* main.py: Contains the Streamlit application code, handling the UI and model integration.
* prediction_helper.py: Helper functions used to preprocess data and make predictions.

#### Technology Stack
* Programming Language: Python
* Libraries: pandas, numpy, scikit-learn, xgboost, Streamlit, matplotlib, seaborn
* Deployment: Streamlit Cloud

#### Click the below link to run the app
[Health Insurance Premium Predictor](https://shield-health-insurance-prediction.streamlit.app/)

