Customer Churn Prediction using ANN

Project Overview
This project aims to predict customer churn for a telecom company using a deep learning approach with an Artificial Neural Network (ANN). The dataset is sourced from Kaggle and contains customer information, including demographics, account details, and service usage metrics. The goal is to build a model that can effectively identify customers at risk of leaving, enabling proactive retention strategies.

Dataset
Source: Kaggle Customer Churn Dataset
Features: The dataset includes various features such as customer demographics, services subscribed, and historical churn information.
Methodology
Data Preprocessing:
Loaded the dataset and performed exploratory data analysis (EDA).
Handled missing values and removed duplicates.
One-hot encoded categorical variables and scaled numerical features.
Model Architecture:
Constructed a Sequential ANN model with the following layers:
Input layer
Hidden layers with ReLU activation
Output layer with a sigmoid activation function for binary classification.
Compilation and Training:
Compiled the model using binary cross-entropy loss and the Adam optimizer.
Split the data into training and testing sets.
Trained the model on the training dataset.
Evaluation:
Evaluated the model's performance using accuracy, precision, recall, 
This project demonstrates the application of ANN in predicting customer churn, showcasing the potential for machine learning to drive business decisions and enhance customer retention strategies. The model's insights can be used to target at-risk customers with tailored retention offers.

Requirements
Python 3.x
TensorFlow
Pandas
NumPy
Scikit-learn
