# PRODIGY_DS_Task02
Data analysis and visualization of the Titanic dataset using preprocessing and EDA techniques.
# PRODIGY_DS_Task2

## Introduction
This repository contains the second task of the Prodigy Data Science Internship. The task focuses on analyzing the Titanic dataset using data preprocessing, visualization, and exploratory data analysis (EDA) techniques.

# Titanic Dataset Analysis

## About the Dataset
The dataset contains information about Titanic passengers, including demographic details, ticket class, fare, and survival status. The key columns in the dataset are:
- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1st, 2nd, or 3rd)
- **Name**: Passenger name
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger (some missing values filled with mean age)
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Ticket fare
- **Embarked**: Port of embarkation

## Task Overview
The following steps were performed as part of the analysis:
1. **Data Cleaning**: 
   - Dropped the 'Cabin' column due to many missing values.
   - Filled missing 'Age' values with the mean age.
   - Filled missing 'Embarked' values with the mode (most frequent value).
2. **Exploratory Data Analysis (EDA)**:
   - Visualized survival counts and trends based on gender, ticket class, and age groups.
   - Created histograms and bar charts to understand survival distributions.
   - Used a heatmap to analyze correlations between numerical variables.

## Knowledge Gained
- The survival rate was higher for females compared to males.
- Passengers from higher ticket classes had a better survival rate.
- Age played a crucial role, with infants and young children having higher survival rates.
- The correlation heatmap helped in identifying relationships between numerical variables.

## Conclusion
This analysis provided valuable insights into how different factors influenced survival rates on the Titanic. The project reinforced the importance of data preprocessing and visualization in extracting meaningful patterns from real-world datasets.


