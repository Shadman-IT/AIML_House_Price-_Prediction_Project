# AIML_House_Price-_Prediction_Project
Project Title: Maharashtra House Price Prediction using Linear Regression

Member Information:
Name: Mohammed Shadman
Roll No.: 2023BIT018
Role / Work Done: Developed the dataset, trained the Linear Regression model, implemented house price prediction functionality, and prepared project files for submission.

Project Description:
This project is a House Price Prediction System for selected cities in Maharashtra — Nanded, Parbhani, and Basmat. The system predicts the estimated price of a house based on user inputs such as city, area (sq.ft), number of bedrooms, number of bathrooms, and age of the house. The project uses a Linear Regression algorithm trained on a realistic dataset of 50 houses. It calculates house prices using the Normal Equation for regression, providing quick and realistic price predictions.

Technologies & Algorithms Used:
Algorithm: Linear Regression (Normal Equation)
Dataset: Realistic dataset of 50 houses across Nanded, Parbhani, and Basmat
Libraries: NumPy, Pandas, Joblib
Programming Language: Python
Development Environment: Google Colab

How the Project Works:
Dataset Creation: A realistic dataset of 50 houses with columns: city, area, bedrooms, bathrooms, age, and price.
Encoding City: City names are encoded numerically for use in Linear Regression.
Model Training: Linear Regression is trained using the Normal Equation on the dataset. Model weights (theta) are calculated and saved.
Price Prediction: User inputs city, area, bedrooms, bathrooms, and age. The trained model predicts the estimated house price.

Sample Input and Output:
Input: City: Nanded, Area: 1500 sq.ft, Bedrooms: 4, Bathrooms: 3, Age: 5
Output: Predicted Price: ₹58,000,000

Project Files:
house_price_realistic_dataset.csv → The dataset of 50 houses
house_price_model_realistic.pkl → Trained Linear Regression model
train_house_price_model.ipynb → Notebook for training the model
predict_house_price.ipynb → Notebook for user input and price prediction

Tools Used: Python 3.x, Google Colab, Libraries: NumPy, Pandas, Joblib
