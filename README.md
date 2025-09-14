# 🩺 Stroke Prediction System Web App

A full-stack web application for predicting stroke risk using Machine Learning, developed with React (frontend) and Flask (backend). It integrates a trained ML model to provide real-time health predictions from user medical data.

📑 Table of Contents
- Project Structure
- Features
- Screenshots
- Installation and Setup
- Usage
- Technologies
- File Overview
- Author

📂 Project Structure
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
│   │   ├── App.css
│   │   ├── App.js
│   │   ├── App.test.js
│   │   ├── index.css
│   │   ├── index.js
│   │   ├── logo.svg
│   │   ├── reportWebVitals.js
│   │   └── setupTests.js
│   ├── package-lock.json
│   ├── package.json
│   └── README.md
├── .gitignore

✨ Features
- 🖥️ User-friendly React frontend for entering medical data  
- ⚡ Flask backend API serving a trained stroke prediction model  
- 🤖 Machine learning model (.joblib) created from stroke-data.csv  
- ⏱️ Real-time prediction and feedback  
- 🔧 Modular code for easy extension and retraining  

📸 Screenshots
Here are some sample UI previews of the Stroke Prediction Web App:
<img width="1884" height="913" alt="Screenshot 2025-07-17 033143" src="https://github.com/user-attachments/assets/12c33a87-5ccb-4b1e-8fb8-ef7f554a57b1" />


> Place your actual screenshots inside a `screenshots/` folder in the project root and update the image paths above.

⚙️ Installation and Setup
### Backend
Install Python dependencies:
```bash
pip install flask joblib pandas scikit-learn
