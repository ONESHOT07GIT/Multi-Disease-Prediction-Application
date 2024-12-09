# Multi-Disease Prediction App

## Overview
The **Multi-Disease Prediction App** is an interactive web application designed to predict the likelihood of diabetes, heart disease, and kidney disease. Built using Python and Streamlit, this app integrates machine learning models and a user-friendly interface for seamless operation. It enables healthcare professionals and users to input specific medical data and receive real-time predictions.

## Features
- Predicts the likelihood of three diseases: Diabetes, Heart Disease, and Kidney Disease.
- Interactive UI with dropdowns and input fields for user convenience.
- Utilizes pre-trained machine learning models stored in Pickle format for high accuracy.
- Offers intuitive navigation with a sidebar for disease selection.
- Real-time results with visual feedback.

## Tools & Technologies
- **Programming Language**: Python
- **Libraries**: Streamlit, Pandas, Numpy, Sklearn, Pickle, OS
- **Models**: Pre-trained Machine Learning Models (Gradient Boosting, Random Forest, etc.)
- **Data Preprocessing**: Feature encoding, data scaling, and outlier removal.

## Code Structure
### 1. Application Initialization
- **Streamlit Initialization**: Set up the app layout, sidebar, and titles.
- **Model Loading**: Load pre-trained models using Pickle.

### 2. User Input
- **Input Fields**: Create columns and input boxes for collecting user data like glucose level, blood pressure, BMI, etc.
- **Validation**: Ensure the correctness of input data types.

### 3. Prediction Logic
- **Data Preparation**: Convert user inputs into the format required by the ML models.
- **Model Predictions**: Call the respective model (Diabetes, Heart Disease, Kidney Disease) for predictions.

### 4. Result Display
- **Feedback**: Display success messages indicating whether the user has a specific disease or not.
- **Dynamic Visualization**: Optional integration of visual elements for better user insights.
