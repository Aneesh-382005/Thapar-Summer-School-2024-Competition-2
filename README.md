# Thapar-Summer-School-2024-Competition-2:  Predicting Patient Status with RandomForest

This repository contains my submission to Thapar-Summer-School-2024-Competition-2 which is focused on predicting patient status using medical data. 
It involves using RandomForest for classification and Optuna for hyperparameter tuning to maximize the accuracy of predictions.

## Table of Contents

## Project Overview

The goal of this project is to predict the patient status (`NObeyesdad`) based on various medical attributes. The target variable `NObeyesdad` includes several categories such as `Insufficient_Weight`, `Normal_Weight`, `Overweight_Level_I`, `Overweight_Level_II`, `Obesity_Type_I`, `Obesity_Type_II`, and `Obesity_Type_III`.

## Dataset

The dataset consists of 18 columns, including:

- `id`: Unique identifier for each record
- `Gender`: Gender of the patient
- `Age`: Age of the patient
- `Height`: Height of the patient
- `Weight`: Weight of the patient
- `family_history_with_overweight`: Family history with overweight
- `FAVC`: Frequency of high-caloric food consumption
- `FCVC`: Frequency of vegetable consumption
- `NCP`: Number of main meals per day
- `CAEC`: Consumption of food between meals
- `SMOKE`: Smoking habit
- `CH2O`: Daily water intake
- `SCC`: Calories consumption monitoring
- `FAF`: Physical activity frequency
- `TUE`: Time using technology devices
- `CALC`: Alcohol consumption
- `MTRANS`: Transportation method
- `NObeyesdad`: Target variable indicating the patient's obesity level

## Installation

To run this project locally, you'll need Python and the following libraries:

```bash
pip install pandas numpy scikit-learn optuna
