MediPredict AI — Disease Prediction System
A machine learning-powered web app that predicts diseases based on patient symptoms.

How It Works
A Gaussian Naive Bayes classifier is trained on 1,600 patient records across 8 diseases and 20 binary symptoms. The trained model parameters are embedded directly in the HTML file, so inference runs entirely in the browser.

Features
Diagnose Tab — Select symptoms and get an instant AI-powered diagnosis with confidence scores
Model Performance Tab — View accuracy metrics, confusion matrix, and feature importance
About Tab — Explanation of the model, the math, and ethical limitations

Diseases Covered
Malaria, Influenza, Dengue, Typhoid, Cholera, Pneumonia, Common Cold, Hepatitis
Model Performance
ModelAccuracyNaive Bayes65.9%Decision Tree50.3%

Tech Stack
Python — Model training (scikit-learn, pandas, numpy)
Vanilla HTML/CSS/JS — Frontend GUI (zero dependencies)

Disclaimer
This tool is for educational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment.
