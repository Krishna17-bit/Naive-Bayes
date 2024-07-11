## Overview
The project explores a classic problem in the field of machine learning and data analysis—predicting salaries based on factors like age, education, occupation, and more. We utilize logistic regression and Naive Bayes classifiers to model and predict salary classes.

## Data Description
The dataset includes the following fields:

- age: The age of the individual.
- workclass: The type of employment of the individual (e.g., Private, Self-emp).
- education: Highest level of education achieved.
- educationno: Highest level of education in numerical form.
- maritalstatus: Marital status of the individual.
- occupation: Job occupation.
- relationship: Relationship status.
- race: Race of the individual.
- sex: Gender of the individual.
- capitalgain: Monetary capital gains.
- capitalloss: Monetary capital losses.
- hoursperweek: Number of hours worked per week.
- native: Native country.
- Salary: Salary class (<=50K or >50K).

## Data files:
- SalaryData_Train.csv: Training data containing 30,161 entries.
- SalaryData_Test.csv: Test data containing 15,060 entries.

## Library Usage
The project uses several libraries:

- Pandas and NumPy for data handling.
- Matplotlib and Seaborn for visualizations.
- Scikit-learn for modeling and predictions.
- Statsmodels for more statistical approaches in Python.
- Category Encoders for handling categorical variables.
