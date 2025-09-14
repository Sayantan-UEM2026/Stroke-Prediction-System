# Stroke-Prediction-System Web App
A full-stack web application for predicting stroke risk using machine learning, developed with React (frontend) and Flask (backend). Integrates a trained model for real-time health predictions from user medical data.

Table of Contents
Project Structure

Features

Installation and Setup

Usage

Technologies

File Overview

Author

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

Installation and Setup
Backend
Install Python dependencies:

bash
pip install flask joblib pandas scikit-learn
Run the backend server:

bash
cd backend
python app.py
Frontend
Navigate to frontend directory:

bash
cd frontend
Install npm dependencies and start the React app:

bash
npm install
npm start
Open http://localhost:3000 to access the app.

Usage
Enter medical data in the frontend form.

Submit to get stroke risk prediction from the backend ML model.

Technologies
Frontend: React, CSS

Backend: Flask (Python)

Machine Learning: scikit-learn, pandas, joblib

Deployment: Localhost development server

File Overview
app.py: Flask backend API server.

training.py: Script to train and save the ML model.

stroke_prediction_model.joblib: Saved ML model artifact.

stroke-data.csv: Dataset used for training.

Frontend React files (App.js, index.js, App.css etc).

Author
Sayantan Sadhukhan
