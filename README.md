# PROJECT's KAGGLE LINK : 
***https://www.kaggle.com/code/dvaser/heart-attact-analysis-prediction/***

<a href="https://www.kaggle.com/code/dvaser/heart-attact-analysis-prediction/">
    <img src="https://github.com/user-attachments/assets/a81b1b11-476d-44b8-9cfb-3b283929fd38" style="width:75%;"></img>
</a>

# HEART ATTACK ANALYSIS & PREDICTION

## What will you learn from this project?
* EDA
* Missing Value Analysis
* Categoric and Numeric Features
* Standardization
* Box - Swarm - Cat - Correlation
* Outlier Detection
* ML Modelling and Tuning Machine Learning Model

## Introduction
* A heart attact, also called a myocardial infarction, happens when a part of the heart muscle doesn't get enough blood.
* The more time that passes without treatment to restore blood flow, the greater the damage to the heart muscle.
* Coronary artery disease (CAD) is the main cause of heart attack.

<img src="https://github.com/user-attachments/assets/e908492f-8996-4eef-b327-f35fb43def2d" style="width:75%;"></img>

## Analysis Content
1. [Python Libraries](#1)
2. [Data Content](#2)
3. [Read & Analyse Data](#3)
4. [Missing Value Analysis](#4)
5. [Unique Value Analysis](#5)
6. [Categorical Feature Analysis](#6)
7. [Numeric Feature Analysis](#7)
8. [Standardization](#8)
9. [Box Plot Analysis](#9)
10. [Swarm Plot Analysis](#10)
11. [Cat Plot Analysis](#11)
12. [Correlation Analysis](#12)
13. [Outlier Detection](#13)
14. [Modelling](#14)
    1. [Encoding Categorical Columns](#14.1)
    2. [Scaling](#14.2)
    3. [Train/Test Split](#14.3)
    4. [Logistic Regression](#14.4)
    5. [Logistic Regression Hyperparamater Tuning](#14.5)
15. [Conclusion](#15)

---

## Data Content
* Age : Age of the patient
* Sex : Sex of the patient
* exang: exercise induced angina (1 = yes; 0 = no)
* ca: number of major vessels (0-3)
* cp : Chest Pain type chest pain type
    * Value 1: typical angina
    * Value 2: atypical angina
    * Value 3: non-anginal pain
    * Value 4: asymptomatic
* trtbps : resting blood pressure (in mm Hg)
* chol : cholestoral in mg/dl fetched via BMI sensor
* fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* rest_ecg : resting electrocardiographic results
    * Value 0: normal
    * Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    * Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
* thalach : maximum heart rate achieved
* target : 0= less chance of heart attack 1= more chance of heart attack
---

