# Heart Disease Prediction Project

Project Overview

This project uses machine learning to predict the presence of heart disease in patients based on various medical attributes. The model is built using Logistic Regression and achieves good accuracy in classifying whether a person has heart disease or not.

Features

-  Data Analysis: Comprehensive exploration of the heart disease dataset
  
-  Machine Learning: Implementation of Logistic Regression classifier
  
-  Model Evaluation: Accuracy assessment on both training and test data
  
-  Predictive System: Ability to make predictions on new patient data

Dataset

The dataset contains 303 samples with 14 attributes:

-  age: Age in years
  
-  sex: Gender (1 = male, 0 = female)
  
-  cp: Chest pain type (0-3)
  
-  trestbps: Resting blood pressure (mm Hg)
  
-  chol: Serum cholesterol (mg/dl)
  
-  fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
  
-  restecg: Resting electrocardiographic results (0-2)
  
-  thalach: Maximum heart rate achieved
  
-  exang: Exercise induced angina (1 = yes, 0 = no)
  
-  oldpeak: ST depression induced by exercise relative to rest
  
-  slope: Slope of the peak exercise ST segment
  
-  ca: Number of major vessels colored by fluoroscopy (0-3)
  
-  thal: Thalassemia (1-3)
  
-  target: Heart disease presence (1 = yes, 0 = no)

Model Performance

-  Training Accuracy: 85.12%
  
-  Test Accuracy: 81.97%

How to Use

-  Clone this repository
  
-  Install required dependencies: numpy, pandas, scikit-learn
  
-  Run the Jupyter notebook to train the model
  
-  Use the predictive system to make new predictions


Example Prediction

python

Example input: (age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal)

input_data = (62, 0, 0, 140, 268, 0, 0, 160, 0, 3.6, 0, 2, 2)

Prediction: 0 (No Heart Disease)


Files in Repository
-  Project_6_Heart_Disease_Prediction.ipynb: Main Jupyter notebook with code
  
-  heart_disease_data.csv: Dataset file
  
-  README.md: This documentation file

Requirements

-  Python 3.x
  
-  Jupyter Notebook
  
-  NumPy
  
-  Pandas
  
-  Scikit-learn

Future Improvements

-  Experiment with other classification algorithms
  
-  Implement feature engineering

  

Create a web interface for the model

Add cross-validation for better model evaluation
