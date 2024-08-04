# Heart Attack Analysis and Prediction

## Overview

This data science project focuses on analyzing and predicting the likelihood of heart attacks using a dataset sourced from Kaggle. The goal is to build a model that can accurately predict the risk of a heart attack based on various health indicators and medical data.

## Dataset

The dataset includes the following features:

- **Age**: Age of the patient
- **Sex**: Sex of the patient
- **exang**: Exercise-induced angina (1 = yes; 0 = no)
- **ca**: Number of major vessels (0-3)
- **cp**: Chest pain type
  - Value 1: Typical angina
  - Value 2: Atypical angina
  - Value 3: Non-anginal pain
  - Value 4: Asymptomatic
- **trtbps**: Resting blood pressure (in mm Hg)
- **chol**: Cholesterol in mg/dl fetched via BMI sensor
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **rest_ecg**: Resting electrocardiographic results
  - Value 0: Normal
  - Value 1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - Value 2: Showing probable or definite left ventricular hypertrophy by Estes' criteria
- **thalach**: Maximum heart rate achieved
- **target**: Heart attack risk indicator (0 = less chance of heart attack, 1 = more chance of heart attack)

## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset used for analysis and model training
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model development
- `models/`: Saved models and model evaluation results
- `README.md`: Project overview and documentation

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/heart-attack-prediction.git
