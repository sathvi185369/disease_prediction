# 🩺 Disease Prediction using Machine Learning

An intelligent, web-based diagnostic tool that predicts diseases based on symptoms using trained classification models. Built with Django, this project takes user inputs (symptoms and personal details) and suggests a likely disease along with the appropriate doctor to consult.

## 🔍 Features

- 🔐 User Authentication: Secure signup and login functionality
- 📝 Symptom-based Input: Collects patient details and up to 10 symptoms
- 🧠 Disease Prediction: Predicts the disease using trained models (Random Forest, Naive Bayes, Decision Tree)
- 👨‍⚕️ Doctor Recommendation: Suggests the relevant specialist for treatment
- 💡 User-friendly Interface: Clean, responsive frontend using HTML, CSS, and JavaScript


### 🏠 Home Page

![image alt](https://github.com/sathvi185369/disease_prediction/blob/376ecce8fdd22c9c02f26948b425a692d2166442/Screenshot%202025-08-04%20225056.png)
- Login / Signup access
- "Not feeling well?" button for diagnosis



### 👤 Patient Details Form

![image alt](https://github.com/sathvi185369/disease_prediction/blob/142c6af315b1546c1ac52e451eb93e29b934dfa8/Screenshot%202025-08-04%20225408.png)
- Enter name, age, gender, height, weight
- Choose 10 symptoms from a dropdown



### 📄 Prediction Result

![image alt]()
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
