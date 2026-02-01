# Automated-Depression-Prediction-Using-NLP
Automated Depression Prediction using NLP and Machine Learning. This project analyzes user-written text and predicts depression using TF-IDF, machine learning models, and a Flask-based web interface.
# Automated Depression Prediction Using NLP

This project predicts whether a person is experiencing depression by analyzing
text input using Natural Language Processing (NLP) and Machine Learning techniques.
The system converts text into numerical features using TF-IDF and classifies it
using trained machine learning models. The final model is deployed as a web
application using Flask.

---

## 📌 Features
- Text preprocessing and cleaning
- Feature extraction using TF-IDF
- Machine learning-based depression classification
- Web-based prediction interface using Flask
- Fast and privacy-friendly mental health screening

---

## 🛠️ Technologies Used
- Python
- Natural Language Processing (NLP)
- Machine Learning
- Pandas, NumPy
- Scikit-learn
- CatBoost
- Flask (Web Framework)

---

## 🧠 Machine Learning Models
- Logistic Regression
- Decision Tree
- AdaBoost
- CatBoost (Best Performing Model)

---

## ⚙️ Project Modules

### 1. Data Preprocessing
- Cleans raw text data
- Removes stop words and symbols
- Converts text into numerical features using TF-IDF

### 2. Model Training & Evaluation
- Trains multiple machine learning models
- Evaluates accuracy and performance
- Selects the best model for prediction

### 3. Prediction
- Takes new user text as input
- Applies preprocessing and feature extraction
- Predicts depression or non-depression

### 4. Deployment
- Saves trained model using pickle
- Deploys model using Flask web application
- Displays prediction result to the user

---

## 🚀 How to Run the Project

1. Clone the repository
```bash
git clone https://github.com/your-username/depression-prediction-nlp.git
