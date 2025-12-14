#**Titanic Data Preprocessing Project**

Dataset
- **Dataset used:** Titanic dataset passenger data - Kaggle

- **Objective:** Explore and preprocess data to prepare a clean dataset for analysis and machine learning.
Preprocessing Steps
1. Checked missing values and handled them:
- Age: filled with median
- Embarked: fill in with most common value
- Cabin: omitted because of too many missing values
2. Dropped unnecessary columns: Name, Ticket, PassengerId
3. Encoded categorical variables:
- Sex: male=0, female=1

- Embarked: one-hot encoding
4. Exported cleaned dataset as titanic_clean.csv
Machine Learning Baseline
It uses all the predictor variables, since collinearity isn't an issue here. Model used: Logistic Regression.
- **Features:** Pclass, Sex, Age, SibSp, Parch, Fare, Embarked preprocessed
- **Target:** Survived

- Accuracy: 81%
Confusion matrix, precision, recall, F1-score computed.
- Acts as a naive baseline; can be enhanced further with higher models or feature engineering.


Deliverables - Titanic_Data_Preprocessing.ipynb (Colab notebook)
titanic_clean.csv (cleaner data set) 
This README.md file
