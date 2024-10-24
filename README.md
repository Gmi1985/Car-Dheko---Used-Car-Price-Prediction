# Advanced Data Processing and Machine Learning Model Deployment

## Project Overview

This repository contains the necessary files for deploying a machine learning model using Streamlit. The project involves preprocessing datasets, training a model with XGBoost, and developing a web application to interact with the model predictions.

## Installation

Clone this repository and install the necessary dependencies:

git clone (https://github.com/Gmi1985/Car-Dheko---Used-Car-Price-Prediction.git)

pip install -r requirements.txt


Usage
Run the Streamlit application locally by navigating to the repository's directory and using the following command:
streamlit run app.py

Make sure to replace app.py with the path to the script if it is different.

Structure
app.py: The main Streamlit application script.
dataformat.ipynb, datapreprocessing.ipynb, datastandardisation.ipynb: Jupyter notebooks for data formatting, preprocessing, and standardization.
scaler.pkl, labelencoded.pkl, onehotencoded.pkl, best_xgb_model.pkl: Serialized files for the scaler, label encoder, one-hot encoder, and the trained XGBoost model.
requirements.txt: Contains all the necessary Python packages.

Features
Data Visualization: Utilizing Matplotlib, Seaborn, and Plotly for insightful data visualizations.
Model Training and Evaluation: Employing Scikit-learn and XGBoost for model training and evaluation.
Web Application: Deployment of a machine learning model using Streamlit for easy interaction.
