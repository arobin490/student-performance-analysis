Student Performance Analysis & Grade Prediction
Project Overview

This project analyzes student academic performance using real-world educational data and applies statistical analysis and machine learning techniques to identify the key factors influencing final grades (G3).

The goal is to understand how academic behavior, family background, and lifestyle choices impact student outcomes and to build a predictive model for academic performance.

Dataset
Source: Kaggle Student Performance Dataset
Features: 30+ variables including:
Study habits (study time, absences)
Academic history (G1, G2, G3)
Family background (parent education, support)
Lifestyle factors (alcohol consumption, free time)

Target variable:

G3 (Final Grade)
Objective
Identify key factors influencing student performance
Perform exploratory data analysis (EDA)
Visualize relationships between variables
Build a machine learning model to predict final grades
Interpret feature importance for real-world insights

Methodology
1. Data Cleaning & Exploration
Loaded dataset using Pandas
Checked missing values and data structure
Generated descriptive statistics
2. Exploratory Data Analysis (EDA)
Distribution analysis of final grades
Relationship analysis (study time, absences vs grades)
Group comparisons (family support, alcohol consumption)
Correlation heatmap of numeric features
3. Data Visualization
Histograms for grade distribution
Scatter plots for behavioral relationships
Bar charts for categorical comparisons
Correlation heatmap for feature relationships
4. Machine Learning Model
Model: Random Forest Regressor
Train-test split applied (80/20)
Model trained to predict G3 based on student features
Evaluation using MAE and R² score
5. Feature Importance Analysis
Identified most influential factors in predicting student performance

Key Findings
Prior academic performance (G1, G2) is the strongest predictor of final grade
Absences negatively impact academic performance
Study time shows a positive correlation with grades
Alcohol consumption is associated with lower academic performance
Family and school support have moderate influence on outcomes

Machine Learning Results
Model: Random Forest Regressor
Output: Predicted student final grades (G3)
Evaluation: Measured using MAE and R² score
Insight: Academic history is more predictive than lifestyle factors

Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Project Structure
student-performance-analysis/
│
├── student_data.csv
├── notebook.ipynb
├── README.md
└── results/

Future Improvements
Try additional models (Linear Regression, XGBoost)
Hyperparameter tuning
Build web dashboard (Streamlit)
Expand dataset to multi-school analysis

Author
Built as an independent data science project exploring educational performance patterns using statistical and machine learning methods.
