# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors that influenced passenger survival. The goal is to analyze the data, identify patterns, handle missing values, and extract meaningful insights using visualization techniques.

This project focuses on data understanding and storytelling rather than predictive modeling.


## Dataset

Source: Kaggle – Titanic: Machine Learning from Disaster

File used:train.csv

Rows:891

Columns:12

The dataset contains passenger information such as age, gender, passenger class, fare, and survival status.


## Tools & Technologies
Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook


## Project Structure

Titanic_EDA/
│
├── Data/
│ └── train.csv
│ └── test.csv
│
├── Notebook/
│ └── titanic_eda.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore



## Analysis Performed

Data loading and inspection
Understanding data types and structure
Missing values analysis
Univariate analysis
Bivariate analysis with survival status
Data visualization and insights



## Key Insights

- Female passengers had a significantly higher survival rate compared to males.

- Passengers traveling in first class were more likely to survive.

- Survival rates varied strongly based on passenger class and gender.

- Missing values were present in the Age, Cabin, and Embarked columns.



## How to Run the Project

1.Download the Titanic dataset from Kaggle.

2.Place `train.csv` inside the `Data/` folder.

3.Open the notebook `titanic\_eda.ipynb`.

4.Run all cells to reproduce the analysis.

## Conclusion

This exploratory analysis highlights how demographic and socio-economic factors influenced survival outcomes on the Titanic. The insights gained from this EDA can serve as a foundation for further feature engineering and predictive modeling.


## Author

Keerthi Priya

