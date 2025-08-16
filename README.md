# Titanic Survival Prediction
Overview

This project predicts passenger survival on the Titanic using Python. It demonstrates a complete data science workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning with HistGradientBoostingClassifier.

Dataset:

The dataset is sourced from Kaggle’s Titanic: Machine Learning from Disaster competition. It contains passenger demographics, ticket info, and survival outcomes.

Key Steps:

EDA & Insights – Visualized survival trends by age, sex, class, and family size.

Data Cleaning – Imputed missing ages by Pclass/Sex median and filled missing embarked values. Encoded categorical variables.

Feature Engineering – Added FamilySize, Age*Pclass, Age*Sex, Age*FamilySize to capture non-linear effects.

Modeling – Trained HistGradientBoostingClassifier, validated with an 80/20 split, and achieved competitive accuracy.

Results:

Visualizations highlight survival patterns across key features.

Model predictions generated for the test set, ready for Kaggle submission.

Practical Insights:

Features like sex, class, and family size significantly influence survival probability. Engineered features reveal nuanced interactions that improve model performance.

Skills Gained:

Data cleaning and preprocessing

Exploratory analysis and visualization

Feature engineering and correlation analysis

Gradient boosting classification
