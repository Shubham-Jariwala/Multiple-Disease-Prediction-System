# Multiple-Disease-Prediction-System
Multiple Disease Prediction System

Predict diabetes, heart disease, and Parkinson's disease with a single app.

## Overview
This application harnesses the power of machine learning to predict the likelihood of three significant diseases:

### Diabetes

### Heart Disease

### Parkinson's Disease


## Usage

1. Installation

Clone this repository:

`git clone https://github.com/your-username/Multiple-Disease-Prediction-App.git`

Install the required dependencies (listed in requirements.txt):

`pip install -r requirements.txt`

2. Running the App

Launch the app using the command `streamlit run app.py`.

3. Input Data

Enter the relevant information requested by the app. This typically includes:

For diabetes: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age

For heart disease: age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal

For parkinson's: fo, fhi, flo, Jitter_percent, Jitter_Abs, RAP, PPQ, DDP,Shimmer, Shimmer_dB, APQ3, APQ5, APQ, DDA, NHR, HNR, RPDE, DFA, spread1, spread2, D2, PPE

4. Receive Predictions

The app will process the input data and provide predictions for each of the three diseases, on clicking the button.

5. Interpretation

Use the predictions to understand your potential risk for these diseases.
Remember that these predictions are not a substitute for professional medical advice. Consult a healthcare provider for diagnosis and treatment.
Additional Information

## Model Training:

Models used: SVM and Logistic Regression

Dataset source: Kaggle

## Frameworks and Libraries:

numpy==1.21.4

pickle-mixin==1.0.2

streamlit==1.2.0

streamlit_option_menu==0.3.2

scikit-learn==1.0.1

## Contribution:

Explain how others can contribute to the project (e.g., reporting issues, suggesting improvements, submitting pull requests).

## License:

Streamlit Apache 2.0.

## Contact:

Feel free to reach out for any questions or feedback!
