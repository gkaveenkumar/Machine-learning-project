# Multiple Disease Prediction System

## Overview
The **Multiple Disease Prediction System** is a web application developed using machine learning to predict the likelihood of three different diseases:
1. **Diabetes**
2. **Heart Disease**
3. **Parkinson's Disease**

Users can input relevant health parameters, and the system will provide a prediction for each condition.

## Features

### 1. Diabetes Prediction
- **Input Fields**:
  - `Number of Pregnancies`
  - `Glucose Level`
  - `Blood Pressure Value`
  - `Skin Thickness Value`
  - `Insulin Level`
  - `BMI Value`
  - `Diabetes Pedigree Function Value`
  - `Age of the Person`
- **Output**: A prediction indicating the likelihood of diabetes.
- ![Screenshot 2024-11-16 103651](https://github.com/user-attachments/assets/5772b37f-7005-4d03-92e2-bad7b5c91021)



### 2. Heart Disease Prediction
- **Input Fields**:
  - `Age`
  - `Sex`
  - `Chest Pain Types`
  - `Resting Blood Pressure`
  - `Serum Cholesterol in mg/dL`
  - `Fasting Blood Sugar > 120 mg/dL`
  - `Resting Electrocardiographic Results`
  - `Maximum Heart Rate Achieved`
  - `Exercise-Induced Angina`
  - `ST Depression Induced by Exercise`
  - `Slope of the Peak Exercise ST Segment`
  - `Major Vessels Colored by Fluoroscopy`
  - `Thalassemia`
- **Output**: A prediction indicating the likelihood of heart disease.
- ![Screenshot 2024-11-16 103705](https://github.com/user-attachments/assets/a88153a9-938f-4fc8-ade7-0587f609a2df)


### 3. Parkinson's Disease Prediction
- **Input Fields**:
  - Acoustic features related to vocal cord analysis:
    - `MDVP:Fo(Hz)`
    - `MDVP:Fhi(Hz)`
    - `MDVP:Flo(Hz)`
    - `MDVP:RAP`
    - `MDVP:PPQ`
    - `Jitter:DDP`
    - `Shimmer:APQ3`
    - `Shimmer:APQ5`
    - `MDVP:Shimmer`
    - `MDVP:Shimmer(dB)`
    - `Shimmer:DDA`
    - `NHR`
    - `RPDE`
    - `DFA`
    - `Spread1`
    - `Spread2`
    - `D2`
    - `PPE`
- **Output**: A prediction indicating the likelihood of Parkinson's disease.
- ![Screenshot 2024-11-16 103728](https://github.com/user-attachments/assets/6a98383e-feba-4116-8278-7979a41a7e7d)

## Usage
1. Open the application in your browser at the specified URL.
2. Navigate to the desired disease prediction section using the sidebar.
3. Enter the required health parameters in the respective fields.
4. Click the **Test Result** button to view the prediction.

## Technology Stack
- **Backend**: Python, Machine Learning models
- **Frontend**: Streamlit
- **Deployment**: Localhost or cloud hosting platforms

## Installation
```bash
# Clone the repository
git clone <repository-url>

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
