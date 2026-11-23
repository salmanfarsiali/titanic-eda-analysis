# Titanic Dataset – Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic passenger dataset to identify patterns and understand the factors associated with passenger survival.

## Objectives
- Explore and understand the Titanic dataset.
- Identify and handle missing values.
- Perform univariate, bivariate, and multivariate analysis.
- Visualize passenger survival patterns.
- Identify important factors associated with survival.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
```text
titanic-eda-analysis/
├── README.md
├── requirements.txt
├── .gitignore
├── titanic_eda.ipynb
└── data/
    └── titanic.csv
```

## Analysis Performed

### 1. Data Loading and Initial Inspection
Loaded the Titanic dataset and examined its structure, data types, descriptive statistics, and missing values.

### 2. Handling Missing Values
- Examined missing values in the Cabin column.
- Removed the Cabin column due to a high percentage of missing data.
- Filled missing Embarked values using the mode.
- Filled missing Age values using the median.

### 3. Univariate Analysis
- Analyzed the overall survival rate.
- Explored passenger class distribution.
- Visualized passenger age distribution.

### 4. Bivariate and Multivariate Analysis
- Analyzed survival patterns by gender.
- Examined survival rates across passenger classes.
- Compared age distributions of survivors and non-survivors.
- Analyzed survival rates by embarkation port.

## Key Findings
- Female passengers had a significantly higher survival rate than male passengers.
- First Class passengers had better survival chances than Third Class passengers.
- Children appeared to have better survival opportunities than older passengers.
- Sex, Passenger Class, and Age were important factors associated with survival.

## Dataset
Source: https://github.com/datasciencedojo/datasets/blob/master/titanic.csv

## Learning Outcomes
- Data cleaning and preprocessing
- Exploratory Data Analysis
- Missing value handling
- Data visualization
- Statistical interpretation
- Python data analysis libraries
