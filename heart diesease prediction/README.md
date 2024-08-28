# Heart Disease Prediction Using Machine Learning

This project aims to predict the presence of heart disease in patients based on various health parameters using a Machine Learning model. The model is trained using the Naive Bayes algorithm, and the dataset is analyzed to visualize various trends related to heart disease.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Explanation](#model-explanation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Heart disease is one of the leading causes of death worldwide, making early detection essential. This project utilizes a machine learning model to classify whether a patient has heart disease based on parameters such as age, chest pain type, cholesterol levels, and more.

## Dataset

The dataset used in this project is `heart.csv`, which contains the following columns:

- **Age**: Age of the patient
- **Sex**: Gender of the patient
- **ChestPainType**: Type of chest pain (typical angina, atypical angina, non-anginal pain, asymptomatic)
- **RestingBP**: Resting blood pressure
- **Cholesterol**: Serum cholesterol in mg/dl
- **FastingBS**: Fasting blood sugar (1 if > 120 mg/dl, 0 otherwise)
- **RestingECG**: Resting electrocardiographic results
- **MaxHR**: Maximum heart rate achieved
- **ExerciseAngina**: Exercise-induced angina (1 = yes, 0 = no)
- **Oldpeak**: ST depression induced by exercise relative to rest
- **ST_Slope**: Slope of the peak exercise ST segment
- **HeartDisease**: Output class (1 = heart disease, 0 = no heart disease)

## Installation

To run this project, you need to have Python installed on your system. Follow the steps below to set up the environment:

1. Clone the repository:
   ```bash
   git clone https://github.com/jeevabalaji/heart-disease-prediction.git
