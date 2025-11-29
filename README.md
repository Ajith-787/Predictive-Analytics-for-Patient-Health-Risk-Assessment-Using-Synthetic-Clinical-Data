# Predictive-Analytics-for-Patient-Health-Risk-Assessment-Using-Synthetic-Clinical-Data
# Aim of the Study

The aim of this study is to analyze a synthetic patient-health dataset to identify key clinical patterns, explore the relationships among various health indicators, and assess the risk factors associated with eye diseases—specifically diabetic retinopathy. By applying data analytics and visualization techniques, the study seeks to uncover meaningful insights that can support early detection, improve risk assessment, and contribute toward data-driven decision-making in healthcare. Ultimately, the study demonstrates how structured patient data can be leveraged to model and understand health outcomes in a controlled, synthetic environment.

# Problem Definition

Healthcare systems generate vast amounts of patient information, but transforming this data into actionable insights remains a challenge. Clinicians often rely on manual assessment, which can be time-consuming, prone to human error, and limited by the complexity of multi-factor health conditions.

The dataset (patient_data.csv), containing 20,000 patient records with 10 variables, provides an opportunity to explore how machine-learning and statistical analysis can help in:

Identifying relationships between health metrics such as age, blood pressure, glucose level, cholesterol, BMI, lifestyle factors, and disease prevalence

Detecting high-risk patients based on their clinical profile

Predicting the occurrence or severity of certain health conditions

Supporting preventive healthcare strategies through data-guided insights

The core problem is to develop reliable models and analytical methods that can automatically interpret multidimensional patient data, accurately assess risks, and aid in making better-informed healthcare decisions.

# Dataset Description

The dataset patient_data.csv consists of 20,000 synthetic patient records, each containing 10 attributes representing demographic information, health measurements, and disease indicators. The dataset is created to mimic realistic clinical data while avoiding privacy concerns. The variables included are:

name: A unique identifier for each patient (e.g., “Patient 1”). This column is mainly for identification and does not contribute to health-related analysis.

age: The age of the patient, represented as an integer between 30 and 80 years.

has_eye_disease: A boolean value (True/False) indicating whether the patient has any form of eye disease.

has_diabetic_retinopathy: A boolean value (True/False) specifying if the patient has diabetic retinopathy.

This value is True only when has_eye_disease is True, indicating a dependency between the two variables.
sugar_percentage: A floating-point value between 4.0 and 15.0, representing the patient’s sugar level in the body.

glucose_percentage: A float ranging from 70.0 to 200.0, indicating the patient’s glucose level.

cholesterol_percentage: A float between 100.0 and 300.0, representing total cholesterol levels.

obesity_percentage: A float between 15.0 and 40.0, indicating the patient’s body obesity percentage.

blood_pressure: A string formatted as “systolic/diastolic” (e.g., “120/80”), representing the patient’s blood pressure reading.

heart_rate: An integer between 60 and 100, representing the patient’s heart rate in beats per minute.
