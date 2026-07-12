# Titanic Survival Prediction 🚢

## Overview
A machine learning project to predict passenger survival on the Titanic using classification algorithms.

## Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 80% |
| Random Forest | 81% |

Best model: **Random Forest — 81% accuracy**

## Key Findings
- Fare was the strongest predictor of survival — wealthier passengers survived more
- Age was the second most important feature — children were prioritized
- Gender was the third biggest factor — women survived at a much higher rate
- Passengers travelling alone had slightly lower survival rates

## Project Workflow
1. Exploratory Data Analysis — survival by gender, class, age
2. Data Cleaning — handled missing values in Age and Embarked, dropped Cabin
3. Feature Engineering — created family_size and is_alone columns
4. Encoding — converted Sex and Embarked to numeric using get_dummies
5. Model Training — Logistic Regression and Random Forest
6. Evaluation — accuracy score, classification report, feature importance

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook

## Dataset
[Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic)