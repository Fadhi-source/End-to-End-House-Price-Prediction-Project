# End-to-End-House-Price-Prediction-Project
🏠 House Price Prediction | End-to-End Machine Learning Project
Predict house prices using advanced regression techniques and deploy the model as a web app.
Kaggle Dataset: House Prices: Advanced Regression Techniques

📌 Overview
This project demonstrates a complete machine learning workflow to predict house prices based on features like location, size, and number of bedrooms. It includes:

Data cleaning (handling missing values, outliers)

Feature engineering (e.g., "price per square foot")

Model training (Linear Regression, Random Forest, XGBoost)

Hyperparameter tuning with GridSearchCV

Model deployment using Flask and Streamlit

🛠️ Features
Data Preprocessing Pipeline:

Handle missing values and outliers.

Encode categorical variables (e.g., MSZoning = 'RL' → one-hot encoding).

Feature scaling and transformation.

Model Development:

Train and compare multiple regression models.

Optimize hyperparameters for best performance (XGBoost achieved the lowest RMSE).

Deployment:

Flask API: REST endpoint for programmatic predictions.

Streamlit App: User-friendly interface to input features and get predictions.

🚀 Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib/Seaborn

Deployment: Flask, Streamlit, Joblib

Tools: Jupyter Notebook, VS Code, Git


