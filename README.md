# Stroke-Prediction-System Web App
  A full-stack web application for predicting stroke risk using machine learning, developed with React (frontend) and Flask (backend). Integrates a trained model for real-time health predictions from user medical data.

Project Structure
  text
  FLASK_REACT_APP/
  ├── backend/
  │   ├── .ipynb_checkpoints/
  │   ├── app.py
  │   ├── stroke_prediction_model.joblib
  │   ├── stroke-data.csv
  │   └── training.py
  ├── frontend/
  │   ├── node_modules/
  │   ├── public/
  │   ├── src/
  │       ├── App.css
  │       ├── App.js
  │       ├── App.test.js
  │       ├── index.css
  │       ├── index.js
  │       ├── logo.svg
  │       ├── reportWebVitals.js
  │       ├── setupTests.js
  │   ├── package-lock.json
  │   ├── package.json
  │   └── README.md
  ├── .gitignore
Features
  User-friendly React frontend for entering medical data
  
  Flask backend API serving a trained stroke prediction model
  
  Machine learning model (.joblib) created from stroke-data.csv
  
  Real-time prediction and feedback
  
  Modular code for easy extension and model retraining

Usage
  Setup Backend
  
  Install required Python libraries (Flask, joblib, pandas, scikit-learn).
  
  Train the model using training.py or use pre-trained stroke_prediction_model.joblib.

Run the backend:

  bash
  cd backend  
  python app.py
  Setup Frontend

Navigate to /frontend and install dependencies:

  bash
  npm install
  npm start
  Access the app via http://localhost:3000.

Technologies
  Frontend: React, CSS
  
  Backend: Flask (Python)

  ML Libraries: scikit-learn, pandas, joblib

File Overview
  app.py: Main Flask server handling predictions.
  
  training.py: Python script for training and exporting the ML model.
  
  stroke_prediction_model.joblib: Saved ML model for predictions.
  
  stroke-data.csv: Source medical data (training set).
  
  App.js, index.js: Core React components and entry points.

Author
  Sayantan Sadhukhan
