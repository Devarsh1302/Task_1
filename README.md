# Titanic Dataset - Data Cleaning & Preprocessing

## Task Overview

This project is part of an AI & ML Internship focused on **Data Cleaning and Preprocessing** using the Titanic dataset.

### Objective:
To learn how to prepare raw data for machine learning by:
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Outlier detection and removal

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Dataset

The dataset used is the [Titanic Dataset from Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset), which contains information on passengers aboard the Titanic.

---

## Steps Performed

1. **Data Exploration**
   - Checked data types and missing values
   - Reviewed basic statistics with `.describe()`

2. **Missing Value Handling**
   - Replaced missing values in `Age` and `Fare` with the **median**
   - Filled missing `Embarked` values with the **most common value (mode)**

3. **Encoding Categorical Variables**
   - Converted `Sex` and `Embarked` into numeric values using **Label Encoding**

4. **Dropping Irrelevant Features**
   - Removed columns like `Cabin`, `Ticket`, `Name`, and `PassengerId` which don’t contribute to learning

5. **Feature Scaling**
   - Scaled numerical features (`Age`, `Fare`) using **StandardScaler** to normalize the data

6. **Outlier Detection**
   - Visualized with **boxplots**
   - Removed outliers in `Fare` using the **IQR method**

##  Files Included

- `titanic_preprocessing.py`: Python script with all preprocessing steps
- `README.md`: This documentation

## Outcome
The dataset is now clean, ready for training machine learning models, and free from inconsistencies, missing values, and outliers.
