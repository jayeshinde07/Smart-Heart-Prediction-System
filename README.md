 # Smart Heart Prediction System

## 📌 Overview

The Smart Heart Prediction System is a Machine Learning-based web application that predicts the risk of various heart diseases using patient health parameters. The system provides early risk assessment and personalized health recommendations to help users understand their heart health status.

## 🚀 Features

* Predicts multiple heart diseases using Machine Learning.
* User-friendly web interface built with Flask.
* Health parameter input form for diagnosis.
* Personalized health tips and diet recommendations.
* Real-time prediction results.
* Data preprocessing and feature scaling for accurate predictions.

## 🩺 Diseases Predicted

* Coronary Artery Disease (CAD)
* Arrhythmia
* Heart Failure
* Valve Disease
* Cardiomyopathy
* Hypertension

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Python
* Flask

### Machine Learning

* Scikit-learn
* Random Forest Classifier
* Logistic Regression
* Pandas
* NumPy

## 📊 Input Parameters

The system uses health-related parameters such as:

* Age
* Gender
* Chest Pain Type
* Blood Pressure
* Cholesterol Level
* Blood Sugar
* Heart Rate
* BMI
* Smoking Status
* Alcohol Intake
* Physical Activity
* Stress Level
* Family History
* Diabetes
* And other medical indicators

## ⚙️ How It Works

1. User enters health information.
2. Data is preprocessed and scaled.
3. Machine Learning models analyze the data.
4. Disease risk predictions are generated.
5. Health recommendations and diet suggestions are displayed.

## 📂 Project Structure

Smart_Heart_Prediction_System/
│
├── app.py
├── routes.py
├── ml_models.py
├── medical_data.py
│
├── static/
│ ├── css/
│ └── js/
│
├── templates/
│ ├── landing.html
│ ├── input_form.html
│ ├── results.html
│ └── base.html
│
└── dataset/

## ▶️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Smart_Heart_Prediction_System.git
```

2. Navigate to the project directory

```bash
cd Smart_Heart_Prediction_System
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the application

```bash
python app.py
```

5. Open your browser

```bash
http://localhost:5000
```

## 🎯 Future Enhancements

* Deep Learning-based prediction models.
* User authentication system.
* Patient history tracking.
* Cloud deployment.
* Integration with wearable health devices.
* Advanced medical report generation.

## 👨‍💻 Author

**Jayesh Shivaji Shinde**

B.Tech Computer Science & Engineering (Artificial Intelligence)

## 📜 Disclaimer

This project is developed for educational and research purposes only. It should not replace professional medical advice, diagnosis, or treatment.
