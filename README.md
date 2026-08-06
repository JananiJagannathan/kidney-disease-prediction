# CLASSIFYING KIDNEY DISEASE WITH AI REVOLUTIONARY APPROACH TO EARLY DETECTION

## Overview
This project is a Django-based web application designed to classify kidney health conditions using both image uploads and patient data inputs. It was built to demonstrate an end-to-end medical AI deployment with user authentication, prediction results, and a responsive user interface.

## Features
- User registration and login
- Kidney image classification using a trained Keras model
- Patient data-based kidney disease prediction using a pre-trained sklearn model
- Profile management with avatar upload
- Results display and prediction history support

## Technologies Used
- Python
- Django
- TensorFlow / Keras
- scikit-learn / joblib
- Pillow
- Bootstrap
- HTML, CSS, JavaScript

## Project Structure
```text
kidney-disease-prediction/
├── APP/
├── PROJECT/
├── static/
├── templates/
├── media/
├── manage.py
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

## Prerequisites
- Python 3.x
- pip
- Virtual environment support

## Installation
1. Clone the repository
   ```powershell
   git clone <repository-url>
   cd "Deploy\PROJECT"
   ```
2. Create a virtual environment
   ```powershell
   python -m venv venv
   .\venv\Scripts\activate
   ```
3. Install dependencies
   ```powershell
   pip install -r requirements.txt
   ```
4. Configure the database
   - This project uses SQLite by default. No extra database configuration is required for local testing.
5. Run migrations
   ```powershell
   python manage.py migrate
   ```
6. Start the server
   ```powershell
   python manage.py runserver
   ```

## Usage
- Open `http://127.0.0.1:8000` in your browser.
- Register a new user account or log in with existing credentials.
- Use the image upload page for kidney image classification.
- Use the patient information page for data-driven kidney disease prediction.



