# Capstone-Project
# Bedsore Risk Prediction App

#Jackeline Sanchez Olguin
# Biomedical Data Science

##  Project Overview
This project presents an interactive Streamlit web application that estimates a patient’s risk of developing bedsores based on commonly known clinical risk factors.
Pressure ulcers are a frequent and costly complication in hospitalized and immobile patients, yet they are preventable with early identification and intervention.

The goal of this project is to show that with data analysis, statistical modeling, and an application a simple clinical support tool can be developed.

## Data 
A synthetic healthcare dataset was made to represent clinically realistic patient characteristics commonly associated with bedsore development. 
Synthetic data was used to privacy concerns related to patient data and for simplicity. 

Data includes:
- Age  
- Length of hospital stay  
- Diabetes 
- Incontinence 
- Mobility score  
- Nutrition score  

##  Modeling 
A logistic regression model was trained on the synthetic dataset to predict the probability of bedsore development. 

## How to Use the App
1. Launch the app.
2. Adjust the patient characteristics using the sliders and dropdown menus:
   - Age  
   - Length of hospital stay  
   - Diabetes status  
   - Incontinence status  
   - Mobility score  
   - Nutrition score  
3. The app will automatically calculate:
   - The predicted probability of bedsore development  
   - A risk level (Low, Moderate, or High)  
4. Review the suggested preventative actions displayed below the risk prediction.

The app updates results in real time as inputs change.

## Video Presentation Link
https://www.loom.com/share/c3ad93cdccee4fe2ba145c4ef997cc9f

