# Predicting heart disease

Predicting heart disease is a machine learning project that use different types of algorithems
in order to predict whether someone is at risk of having a heart disease. 
The target variable is categorical and the model will be a classification model.

## Features

age-Patient Age in years [Numeric]

sex-Gender (male:1; Female: 0) [Nominal]

cp-Type of chest pain experienced by patient. This term catagorized into 4 catagories. 0 typical anigma, 1 atypical anigma, 2 non-anigmal pain, 3 asymptomatic [Nominal]

trestbsp- patientws level of blood pressure at resting mode in vmm/Hg [numerical]

chol- Serum cholesterol in mg/dl [Numeric]

fsb- Blood suger levels on fasting >120 mg/dl represents 1 in case of true and 0 as false [Nominal]

restecg- Result of electrocardiogram while at rest are represented in 3 distinct values. 0: normal, 1: having ST-T wave abnormality, 2: showing probable or definite left ventricular hypertrophy by Estes criteria [Nominal]

thalach-Maximum heart rate achived [Numeric]

exang- Angina induced by exercise 0 depicting NO 1 depicting YES [Nominal]

oldpeak-Exercise induced ST depression in relative with the state of rest [Numeric]

slope- ST segment measured in terms of slope during peak exercise 
0: up sloping,  1: flat, 2: down sloping [Nominal]

ca- The number of major vassels (0-3) [Nominal]

thal- A blood disorder called thalassemia
0: NULL, 1: normal blood flow, 2 :fixed defect (no blood flow in some part of the heart) 3:reversibale defect ( a blood flow is observed but it is not normai) [Nominal]

target- it is the target variable which we have to predict 1 means patinet is suffering from heart disease and 0 means patient is normal.

## Data

data size- 303 rows and 14 columns

## Model training:

To find the best algorithm, different algorithms of the following types were used:
Decision Tree model, Random forest model, KNN model, SVM, and MLP model. 

## Results

The best model found was KNN model with an accuracy of 84%

## Installation

Python versions 3.*.
Python Libraries:
numpy.
Pandas.
seaborn
matplotlib.
scipy
