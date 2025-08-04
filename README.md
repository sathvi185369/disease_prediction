# 🩺 Disease Prediction using Machine Learning

An intelligent, web-based diagnostic tool that predicts diseases based on symptoms using trained classification models. Built with Django, this project takes user inputs (symptoms and personal details) and suggests a likely disease along with the appropriate doctor to consult.

## 🔍 Features

- 🔐 User Authentication: Secure signup and login functionality
- 📝 Symptom-based Input: Collects patient details and up to 10 symptoms
- 🧠 Disease Prediction: Predicts the disease using trained models (Random Forest, Naive Bayes, Decision Tree)
- 👨‍⚕️ Doctor Recommendation: Suggests the relevant specialist for treatment
- 💡 User-friendly Interface: Clean, responsive frontend using HTML, CSS, and JavaScript


### 🏠 Home Page


- Login / Signup access
- "Not feeling well?" button for diagnosis



### 👤 Patient Details Form
- Enter name, age, gender, height, weight
- Choose 10 symptoms from a dropdown



### 📄 Prediction Result
- View submitted details
- Predicted disease
- Recommended doctor specialization




## 🧠 Machine Learning Models Used
- Random Forest Classifier ✅
- Naive Bayes Classifier ✅
- Decision Tree Classifier ✅

Trained on labeled symptom datasets (`Training.csv` and `Testing.csv`), achieving up to 89% accuracy.

## 👨‍⚕️ Doctor Specializations Mapped
Based on predicted disease, one of the following specialists is suggested:

Cardiologist
-Neurologist
-Dermatologist
-Urologist
-Allergist/Immunologist
-Rheumatologist
-Gastroenterologist
-ENT Specialist
-Orthopedist

## ⭐ Acknowledgements

Scikit-learn for ML models

Django for web framework

HTML/CSS/JS for frontend
