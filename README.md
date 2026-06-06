## Predicting-Diabetes-Risk-and-Glucose-Spikes
This is a machine learning project designed to predict glucose spike risk based on patient demographics, dietary intake, lifestyle factors, and clinical measurements.

## Project Overview
NutriGlyc AI Solutions is a health technology and nutrition analytics company that uses artificial intelligence, machine learning, and nutrition science to help prevent and manage Type 2 Diabetes. The company wants to help people stay healthy by detecting diabetes risks early before the condition becomes serious. The goal is to create a system that can:
- Predict diabetes risk
- Predict blood sugar spikes after meals
- Recommend healthier food choices
- Help doctors and patients make better health decisions

## Problem Statement
Frequent glucose spikes increase the risk of diabetes complications and poor long-term health outcomes. Identifying the factors that drive glucose spikes can support preventive healthcare and personalized nutrition recommendations.

## Project Objective
- Develop a machine learning model to predict glucose spikes.
- Identify the most important factors influencing glucose spikes.
- Generate actionable nutrition and lifestyle recommendations.

## Dataset

The dataset contains 5,000 patient meal records after cleaning with demographic, dietary, lifestyle, and clinical variables.

### Key Features

* Age
* BMI
* Carb Intake
* Glycemic Index
* Glycemic Load
* Fiber Intake
* Physical Activity
* Stress Level
* Insulin Dose
* Pre-Meal Glucose

## Feature Engineering

Created additional features:

* Glycemic Index and Portion Size Interaction
* Meal Risk Score
* Fiber Protection
* Activity-Carb Ratio
* Insulin Efficiency

## Models Evaluated

* Logistic Regression
* Random Forest
* XGBoost

## Final Results

| Model                     | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
| ------------------------- | -------- | --------- | ------ | -------- | ------- |
| Tuned Logistic Regression | 76.5%    | 73.1%     | 78.0%  | 75.4%    | 85.9%   |
| Tuned Random Forest       | 77.0%    | 73.6%     | 78.4%  | 75.9%    | 85.0%   |
| Tuned XGBoost             | 77.3%    | 74.1%     | 78.4%  | 76.2%    | 85.3%   |

## Key Findings

Top drivers of glucose spikes include: 
* Carb Intake
* Insulin Efficiency
* Activity-Carb Ratio
* Glycemic Load
* Stress Level

## Recommendations

* Reduce excessive carbohydrate consumption per meal.
* Reduce high glycemic load meals.
* Increase dietary fiber consumption.
* Encourage regular physical activity.
* Improve insulin-to-carbohydrate matching.
* Manage stress levels.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* SHAP
* Matplotlib
* Seaborn

