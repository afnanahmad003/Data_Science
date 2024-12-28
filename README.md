# Heart Disease Prediction

This project utilizes machine learning techniques to predict the likelihood of heart disease in patients based on various medical attributes.

## Overview

Heart disease is a leading cause of mortality worldwide. Early detection through predictive modeling can significantly improve patient outcomes. This project employs machine learning algorithms to analyze patient data and predict the presence of heart disease.

## Dataset

The dataset used in this project includes several medical attributes such as age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, and thalassemia.

## Features

- **Age**: Age of the patient
- **Sex**: Gender of the patient (1 = male; 0 = female)
- **Chest Pain Type (cp)**:
  - 0: Typical angina
  - 1: Atypical angina
  - 2: Non-anginal pain
  - 3: Asymptomatic
- **Resting Blood Pressure (trestbps)**: Resting blood pressure (in mm Hg)
- **Serum Cholesterol (chol)**: Serum cholesterol in mg/dl
- **Fasting Blood Sugar (fbs)**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **Resting Electrocardiographic Results (restecg)**:
  - 0: Normal
  - 1: Having ST-T wave abnormality
  - 2: Showing probable or definite left ventricular hypertrophy
- **Maximum Heart Rate Achieved (thalach)**: Maximum heart rate achieved
- **Exercise-Induced Angina (exang)**: Exercise-induced angina (1 = yes; 0 = no)
- **ST Depression Induced by Exercise (oldpeak)**: ST depression induced by exercise relative to rest
- **Slope of the Peak Exercise ST Segment (slope)**:
  - 0: Upsloping
  - 1: Flat
  - 2: Downsloping
- **Number of Major Vessels (ca)**: Number of major vessels (0-3) colored by fluoroscopy
- **Thalassemia (thal)**:
  - 1: Normal
  - 2: Fixed defect
  - 3: Reversible defect

## Methodology

1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
2. **Exploratory Data Analysis (EDA)**:
   - Statistical analysis
   - Visualization of feature distributions
   - Correlation analysis
3. **Modeling**:
   - Implementation of machine learning algorithms such as Logistic Regression, Decision Trees, Random Forest, K-Nearest Neighbors, and Support Vector Machines
   - Hyperparameter tuning
4. **Evaluation**:
   - Model performance assessed using metrics like accuracy, precision, recall, and F1-score

## Results

The models were trained and evaluated to determine their effectiveness in predicting heart disease. The performance metrics for each model are documented in the notebook.

## Usage

To explore the analysis and results, open the `Heart_Disease_Prediction.ipynb` notebook. Ensure you have the necessary Python libraries installed, such as pandas, numpy, scikit-learn, and matplotlib.

## Conclusion

This project demonstrates the application of machine learning techniques in predicting heart disease, highlighting the importance of data preprocessing, exploratory analysis, and model evaluation in developing effective predictive models.

---

*Note: This `README.md` provides a structured overview of the project. For detailed code and analysis, please refer to the Notebook.*
