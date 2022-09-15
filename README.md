# Heart-Desease-Prediction
Project Overview
Heart disease describes a range of conditions that affect heart. Today, 
cardiovascular diseases are the leading cause of death worldwide with 17.9 
million deaths annually, as per the World Health Organization reports [1]. 
Various unhealthy activities are the reason for the increase in the risk of heart 
disease like:
 High Cholesterol 
 Obesity
 High Blood Pressure
 Lack of Exercises
 Increase in Triglycerides levels, 
 Stress
 Smoking
 Stroke
 Maximum Heart Rate
 Depression
 Fasting Blood Sugar
 Hypertension etc. 
All these symptoms resemble different diseases also like it occurs in the aging 
persons, so it becomes a difficult task to get a correct diagnosis.
But as time is passing, a lot of research data and patients records of hospitals are 
available. There are many open sources for accessing the patient’s records and 
researches can be conducted so that various computer technologies could be 
used for doing the correct diagnosis of the patients and detect this disease to 
stop it from becoming fatal. Nowadays it is well known that machine learning 
and artificial intelligence are playing a huge role in the medical industry. We can 
use different machine learning models to diagnose the disease and classify or 
predict the results. A complete data analysis can easily be done using machine 
learning models. Models can be trained for knowledge predictions and also 
medical records can be transformed and analyzed more deeply for better 
predictions.
The steps we followed in this project:
1. Data Collection
2. Data Cleaning
3. Exploratory data analysis 
4. Feature selection
5. Machine Learning Model develop
 SVM
 KNN
 DT
 LR
 NB
6. Result analysis
Dataset overview
 
 Dataset name: Heart Failure Prediction Dataset
 Attribute Information
1. Age: age of the patient [years]
2. Sex: sex of the patient [M: Male, F: Female]
3. ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: 
Non-Anginal Pain, ASY: Asymptomatic]
4. RestingBP: resting blood pressure [mm Hg]
5. Cholesterol: serum cholesterol [mm/dl]
6. FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7. RestingECG: resting electrocardiogram results [Normal: Normal, ST: having STT wave abnormality (T wave inversions and/or ST elevation or depression of > 
0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by 
Estes' criteria]
8. MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
9. ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
10. Oldpeak: oldpeak = ST [Numeric value measured in depression]
11. ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, 
Down: downsloping]
12. HeartDisease: output class [1: heart disease, 0: Normal]
Source
This dataset was created by combining different datasets already available 
independently but not combined before. In this dataset, 5 heart datasets are 
combined over 11 common features which makes it the largest heart disease 
dataset available so far for research purposes. The five datasets used for its 
curation are:
 Cleveland: 303 observations
 Hungarian: 294 observations
 Switzerland: 123 observations
 Long Beach VA: 200 observations
 Stalog (Heart) Data Set: 270 observations
Total: 1190 observations
Duplicated: 272 observations
Final dataset: 918 observations
Every dataset used can be found under the Index of heart disease datasets 
from UCI Machine Learning Repository on the following 
link: https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/
 Dataset link: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
 Tools used:
 Python
 Jupyter Notebook
 Library:
 Numpy
 Pandas
 Matplotlib
 Seaborn
 Scikit-Learn
 Reference:
1. World Health Organization, Cardiovascular Diseases, WHO, Geneva, 
Switzerland, 2020, https://www.who.int/health-topics/cardiovasculardiseases/#tab=tab_1
