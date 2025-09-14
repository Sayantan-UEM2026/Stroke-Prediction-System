🩺 Stroke Prediction System Web App

A full-stack web application for predicting stroke risk using Machine Learning, developed with React (frontend) and Flask (backend).
It integrates a trained ML model to provide real-time health predictions from user medical data.

📑 Table of Contents

📂 Project Structure

✨ Features

📸 Screenshots

⚙️ Installation and Setup

🚀 Usage

🛠️ Technologies

📄 File Overview

👨‍💻 Author

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

🖥️ User-friendly React frontend for entering medical data

⚡ Flask backend API serving a trained stroke prediction model

🤖 ML model (.joblib) trained on stroke-data.csv

⏱️ Real-time predictions with instant feedback

🔧 Modular design for retraining and easy extension

📸 Screenshots

Here are some sample UI previews of the Stroke Prediction Web App:
<img width="1884" height="913" alt="Screenshot" src="https://github.com/user-attachments/assets/fffee7c1-b6f8-45f7-8ab5-e9bf81dce665" />

⚙️ Installation and Setup
1. Clone the repository
git clone https://github.com/your-username/FLASK_REACT_APP.git
cd FLASK_REACT_APP

2. Set up Backend (Flask + ML model)
cd backend
pip install flask joblib pandas scikit-learn
python app.py

3. Set up Frontend (React)
cd ../frontend
npm install
npm start

4. Open the app

👉 http://localhost:3000

🚀 Usage

Enter medical data in the React form

Submit to send data to Flask API

Receive instant stroke risk prediction

🛠️ Technologies

Frontend: React, CSS

Backend: Flask (Python)

Machine Learning: scikit-learn, pandas, joblib

Deployment: Localhost (development server)

📄 File Overview

backend/app.py → Flask backend API

backend/training.py → Train and save ML model

backend/stroke_prediction_model.joblib → Saved model

backend/stroke-data.csv → Training dataset

frontend/src/ → React components and styles

👨‍💻 Author

Sayantan Sadhukhan
