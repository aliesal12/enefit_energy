# enefit_energy
Enefit - Predict Energy Behavior of Prosumers

Project Overview
Enefit is a project aimed at predicting the energy consumption behavior of prosumers (producers and consumers of energy) using machine learning techniques. This project involves data cleaning, imputation, and the development of a Long Short-Term Memory (LSTM) based neural network model. The ultimate goal is to create a predictive model that accurately forecasts energy usage patterns, which can be beneficial for energy management and planning.

Key Components
Data Imputation

KNN Classifier: Implemented a K-Nearest Neighbors (KNN) classifier to impute missing values for location data based on longitude and latitude coordinates.
Hyperparameter Search: Conducted a hyperparameter search to optimize the KNN classifier, achieving 100% accuracy in predicting location data.
Data Cleaning: Performed extensive data cleaning to prepare the dataset for modeling, ensuring the removal of inconsistencies and errors.
LSTM Neural Network

Model Building: Developed an LSTM-based neural network from scratch to predict energy consumption behavior.
Challenges: Encountered difficulties in achieving high accuracy due to the small size of the model and limited experience with deep learning.
Ongoing Work: The model is still in progress, and efforts are ongoing to enhance its accuracy through further research and experimentation.
Future Work
Model Optimization: Experiment with different architectures, larger models, and advanced techniques to improve prediction accuracy.
Feature Engineering: Explore additional features that could improve the model's performance.
Hyperparameter Tuning: Conduct extensive hyperparameter tuning for the LSTM model.
