## Heart Disease Prediction using Logistic Regression 🫀
Project Overview
This project implements a Logistic Regression model to predict the probability of a patient having heart disease. Logistic Regression was selected because it is a robust baseline for binary classification, providing clear probabilistic outputs and interpretable feature coefficients.

Problem Statement:
One of the hospitals has a patient dataset that contains a wide range of heart-related features. This data allows hospital staff to conduct detailed analyses of heart-related conditions and treatments. We must build a logistic regression model to predict whether a patient has heart disease or not. Calculate the feature importance as well. The dataset contains data for around 303 patients.
 
Data Description:

1. age: Age of the patient in years.
2. gender: Gender of the patient.
3. cp: Chest pain type.
4. trestbps: Resting blood pressure (in mm Hg on admission to the hospital).
5. chol: Serum cholesterol in mg/dl.
6. fbs: fasting blood sugar > 120 mg/dl (1 = true; 0 = false).
7. restecg: Resting electrocardiographic results.
8. thalach: Maximum heart rate achieved.
9. exang: Exercise induced angina (1 = yes; 0 = no).
10. oldpeak: ST depression induced by exercise relative to rest.
11. slope: The slope of the peak exercise ST segment.
12. ca: Number of major vessels (0-3) colored by fluoroscopy.
13. thal: 3 = normal; 6 = fixed defect; 7 = reversible defect.
14. heart_diagnosis: Diagnosis of heart disease (angiographic disease status) (0 = No heart disease, >0 = heart disease).

Implementation Steps

   1. Data Exploration (EDA): Analysing correlations between health metrics like cholesterol and age.
   2. Feature Scaling: Applied StandardScaler to ensure all features contribute equally to the logistic cost function.
   3. Model Training: Using the LogisticRegression class from [Scikit-Learn]
   4. Evaluation: Calculating accuracy, precision, and recall to ensure the model effectively identifies positive cases.

Results
The Logistic Regression model achieved

