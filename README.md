# Fitness Calories Prediction

## Project Overview
This project aims to predict calories burned during workout sessions using physiological, behavioral, and workout-related features. The analysis is based on two independent fitness-related datasets, allowing for data validation, comparison, and predictive modeling.

## Objective
The main goal is to formulate calorie burn prediction as a supervised machine learning regression problem and evaluate how well different models perform on real-world exercise-related data.

## Data Sources
This project uses two independent data sources:

1. Gym Members Exercise Tracking Dataset**
   - File: `gym_members_exercise_tracking.csv`
   - Source: Kaggle dataset on gym member workout tracking

2. Exercise Dataset**
   - File: `exercise_dataset.csv`
   - Source: Kaggle dataset on exercise and fitness metrics

## Project Structure
```text
fitness-calories-prediction/
│
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── 01_fitness_calories_prediction.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── modeling.py
│   └── evaluation.py
├── requirements.txt
└── README.md



