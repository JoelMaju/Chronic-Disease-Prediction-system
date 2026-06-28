# Chronic-Disease-Prediction-system

A web application that predicts the risk of multiple diseases including heart disease, diabetes, stroke, cancer, and obesity using machine learning models. The app also includes user authentication and profile management using MongoDB.

## Features
User registration and login system (Flask + MongoDB + Bcrypt)
User profile dashboard (update name, email, password)
Heart disease risk prediction (Logistic Regression model)
Diabetes risk prediction
Stroke risk prediction (SVM-based model)
Cancer risk prediction model
Obesity / chronic disease prediction model
# Risk classification:
Low Risk
Medium Risk
High Risk
# Personalized health recommendations based on prediction results
 ## Machine Learning Models Used
Logistic Regression (Heart Disease)
SVM (Stroke prediction - external module)
Custom ML pipelines (Diabetes, Cancer, Obesity modules)
StandardScaler for feature normalization
Outlier removal using Z-score filtering

## Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/health-risk-predictor.git
cd health-risk-predictor
2. Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
3. Install dependencies
pip install flask flask-pymongo flask-bcrypt pandas numpy scikit-learn scipy wtforms
## Run the Application
python app.py
