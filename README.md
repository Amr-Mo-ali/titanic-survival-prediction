# 🚢 Titanic Survival Prediction

Binary classification project predicting passenger survival
using Machine Learning.

## 📊 Dataset
- Source: Kaggle Titanic Competition
- 891 samples, 12 features

## 🔨 Pipeline
1. Exploratory Data Analysis
2. Handling missing values (Age, Embarked, Cabin)
3. Feature encoding (Sex, Embarked)
4. Train/Test split (80/20)
5. Model training — Random Forest Classifier
6. Evaluation & Feature Importance Analysis

## 📈 Results
- **Accuracy: 81%**
- Most important feature: **Sex (46%)** — consistent
  with historical "women and children first" policy

## 🛠️ Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib

## 🔍 Key Finding
The model identified Sex as the strongest predictor,
followed by Fare and Pclass — validating the known
historical survival patterns of the Titanic disaster.
``'
