# Real-Estate-Price-Prediction
Real Estate Price Prediction Model using Ridge Regression algorithm trained on preprocessed dataset. Web application built with Flask framework allows users to input location, size, bedrooms, and bathrooms of a property to get an estimate of its price.

Dataset
The dataset used to train and test the model was obtained from the Kaggle Bangalore Real Estate dataset, which contains information about real estate properties in Bangalore, India. The dataset was cleaned and preprocessed before being used to train the model.

Model
The model is based on a Ridge regression algorithm, which was trained on the preprocessed dataset using scikit-learn. The model takes as input the location, size, and number of bedrooms and bathrooms of a property and outputs an estimate of its price.

Flask Web Application
The model was integrated into a web application using Flask, a Python web framework. The web application allows users to input the location, size, and number of bedrooms and bathrooms of a property and receive an estimate of its price based on the trained model. The application also includes a user interface built with HTML and CSS.

Files
Cleaned_data.csv: preprocessed dataset used to train and test the model
train.py: script used to train the Ridge regression model and save it as a pickle file (RidgeModel.pkl)
app.py: Flask application that loads the trained model and serves predictions to users
templates/index.html: HTML template for the user interface
