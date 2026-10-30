# Diabetes Prediction System 

## Project Overview
The Diabetes Prediction System is a Machine Learning-based web application that predicts diabetes outcomes based on user-provided health parameters.

This project uses a trained Random Forest Classification model integrated with Flask to generate predictions through a user-friendly web interface.

##  Features
- Predict diabetes using eight health-related parameters.
- Random Forest classification model.
- Data preprocessing using missing-value imputation.
- Feature scaling.
- Flask-based web application.
- User-friendly HTML and CSS interface.

##  Technologies Used
- Python
- Machine Learning
- Scikit-learn
- Random Forest
- Flask
- NumPy
- HTML
- CSS

## 📂 Project Structure

ProjectDiabetes/
├── app.py
├── rf_model.pkl
├── scaler.pkl
├── imputer.pkl
├── requirements.txt
├── .gitignore
├── README.md
└── templates/
    └── index.html


## ⚙️ Installation and Execution

### 1. Clone the repository


git clone YOUR_GITHUB_REPOSITORY_URL

### 2. Navigate to the project folder


cd diabetes-prediction-ml


### 3. Install dependencies


pip install -r requirements.txt


### 4. Run the Flask application


python app.py


### 5. Open the application

Visit:

http://127.0.0.1:5000/

Enter the required health measurements and click the Predict Diabetes button.

## Learning Outcomes
- Machine Learning model training and testing.
- Data preprocessing techniques.
- Model integration with Flask.
- Development of a complete ML web application.

##  Disclaimer
This project is developed for educational purposes only. It is not a substitute for professional medical diagnosis or advice.