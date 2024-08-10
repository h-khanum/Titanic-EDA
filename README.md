# Exploratory Data Analysis on the Titanic Dataset

## Introduction

This project is an exploratory data analysis (EDA) on the Titanic dataset, which is a popular dataset used in data science and machine learning for educational purposes. The analysis aims to uncover patterns, relationships, and insights about the passengers aboard the Titanic, with a particular focus on understanding the factors that influenced survival rates.

## Dataset

The dataset used in this project contains information about passengers on the Titanic, including their demographics, ticket information, and whether they survived the disaster. The dataset is publicly available and can be found [here](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv).

### Features in the Dataset

- **Survived**: Survival (0 = No, 1 = Yes)
- **Pclass**: Passenger Class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard the Titanic
- **Parch**: Number of parents/children aboard the Titanic
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number (often missing)
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Structure

The project is organized as follows:

- `Titanic_EDA.ipynb`: The Jupyter Notebook containing the full exploratory data analysis, including data cleaning, visualizations, and observations.
- `README.md`: This file, provides an overview of the project.

## Exploratory Data Analysis

The EDA is structured into several sections:

1. **Data Loading and Preliminary Analysis**:
   - Overview of the dataset, including its structure and summary statistics.

2. **Data Cleaning**:
   - Handling of missing values and irrelevant columns.
   - Adjustments made to prepare the data for analysis.

3. **Exploratory Data Analysis**:
   - Distribution analysis of key features such as age, fare, and passenger class.
   - Survival analysis based on various factors including gender, passenger class, and age.
   - Visualizations to illustrate the relationships between different features and survival rates.

4. **Conclusion**:
   - Summary of key findings from the analysis.

## Key Findings

- **Gender**: Females had a significantly higher survival rate than males.
- **Class**: Passengers in the first class were more likely to survive compared to those in the second and third classes.
- **Age**: Children had a higher chance of survival compared to adults, while older passengers had a lower survival rate.

## Requirements

To run the Jupyter Notebook and reproduce the analysis, you need the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib seaborn
