📌 Project Overview

Medical Insurance Cost Prediction is a Machine Learning project that predicts a person's health insurance charges based on demographic and health-related factors such as age, gender, BMI, number of children, smoking status, and region.

The goal of this project is to help insurance companies estimate medical insurance costs more accurately and provide insights into the factors that significantly affect insurance premiums.

🚀 Features
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Data Visualization
Feature Engineering
Machine Learning Model Training
Model Evaluation
Insurance Cost Prediction
Model Saving using Joblib
Streamlit Web Application
📊 Dataset Information

The dataset contains the following features:

Feature	Description
age	Age of the policyholder
sex	Gender (Male/Female)
bmi	Body Mass Index
children	Number of dependents covered
smoker	Smoking status (Yes/No)
region	Residential region
charges	Medical insurance cost (Target Variable)
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib
Streamlit
📈 Exploratory Data Analysis

The following analyses were performed:

Dataset Shape
Data Types
Statistical Summary
Missing Values Analysis
Duplicate Values Check
Unique Values in Categorical Columns
Target Variable Distribution
Correlation Analysis
Age vs Charges
BMI vs Charges
Smoker vs Charges
Sex vs Charges
Region vs Charges
Children vs Charges
Outlier Detection
Pairplot Visualization
🤖 Machine Learning Model

Several regression algorithms can be used:

Linear Regression
Random Forest Regressor
Decision Tree Regressor
Gradient Boosting Regressor
XGBoost Regressor

The best-performing model is selected based on evaluation metrics.

📏 Model Evaluation Metrics

The model is evaluated using:

R² Score
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
💾 Save Trained Model
import joblib

joblib.dump(model, 'insurance_model.pkl')

Load Saved Model:

model = joblib.load('insurance_model.pkl')
🌐 Streamlit Web App

Run the Streamlit application:

streamlit run app.py

The web application allows users to:

Enter personal details
Predict insurance charges instantly
View prediction results through a simple interface
📂 Project Structure
Medical-Insurance-Cost-Prediction/
│
├── dataset/
│   └── insurance.csv
│
├── notebooks/
│   └── Insurance_Cost_Prediction.ipynb
│
├── models/
│   └── insurance_model.pkl
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
📸 Sample Output

Input:

Age: 35
Gender: Male
BMI: 28.5
Children: 2
Smoker: No
Region: Southeast

Output:

Predicted Insurance Cost: $8,750
🎯 Future Improvements
Hyperparameter Tuning
Advanced Feature Engineering
Deployment on Cloud Platforms
Real-time API Integration
Enhanced User Interface
👨‍💻 Author

Pawan Singh

📧 Email: rajputpawan740871@gmail.com
💻 GitHub: Pwn-1651
