# Heart-Disease-Prediction-using-ML
The goal of our heart disease prediction project is to determine if a patient should be diagnosed with heart disease or not, which is a binary outcome, so:

Positive result = 1, the patient will be diagnosed with heart disease.
Negative result = 0, the patient will not be diagnosed with heart disease. 

Features
We use the following 13 features (X) to determine our predictor (Y):

Age.
Sex: 1 = Male, 0 = Female.
(cp) chest pain type (4 values – Ordinal), 1st value: typical angina, 2nd value: atypical angina, 3rd value: non-anginal pain, 4th value: asymptomatic.
(trestbps) resting blood pressure.
(chol) serum cholesterol.
(Fbs) – fasting blood sugar > 120 mg/dl. 
(restecg) – resting electrocardiography results.
(thalach) – maximum heart rate achieved. 
(exang) – exercise-induced angina.
(oldpeak) – ST depression caused by exercise relative to rest.
(slope) – the slope of the peak exercise ST segment.
(ca) – the number of major vessels colored by fluoroscopy.
(thal) – maximum heart rate achieved (Ordinal), 3 = normal, 6 = fixed defect, 7 = reversible defect.


The following Machine Learning algorithms used:

Logistic Regression (Scikit-learn)
Naive Bayes (Scikit-learn)
Support Vector Machine (Linear) (Scikit-learn)
K-Nearest Neighbours (Scikit-learn)
Decision Tree (Scikit-learn)
Random Forest (Scikit-learn)
XGBoost (Scikit-learn)
Artificial Neural Network with 1 Hidden layer (Keras)

Accuracy achieved: 95% (Random Forest)

Dataset find here: https://www.kaggle.com/ronitf/heart-disease-uci
