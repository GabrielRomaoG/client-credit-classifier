# Credit Scoring Project

This project aims to build a predictive model that will tell if a person is a good or bad payer based on the financial data of that given person.

## Project Overview

- Developed a tool to predict whether a customer is likely to be a good or bad payer with a minimum accuracy of 75%.
- Evaluated and compare the performance of two models, logistic regression and naive Bayes, to determine the best model for the task.
- Performed data cleaning and preprocessing to ensure the dataset is suitable for exploratory data analysis (EDA) and model training.
- Conducted an EDA to gain insights into the dataset, including analyzing the distribution of various attributes and their relationships with the target variable.
- Visualized the distributions of selected attributes using appropriate charts and plots.

## Code and Resources Used

Python Version: 3.10.8

packages: pandas, numpy, matplotlib, seaborn, sklearn

## Dataset

The dataset contains 1000 records and you can encounter in this link: [finacial_data](https://archive.ics.uci.edu/ml/machine-learning-databases/statlog/german/german.data).

It includes the following attributes:

1. Status of existing checking account (qualitative)
2. Duration in months (numerical)
3. Credit history (qualitative)
4. Purpose (qualitative)
5. Credit amount (numerical)
6. Savings account/bonds (qualitative)
7. Present employment since (qualitative)
8. Installment rate in percentage of disposable income (numerical)
9. Personal status and sex (qualitative)
10. Other debtors/guarantors (qualitative)
11. Present residence since (numerical)
12. Property (qualitative)
13. Age in years (numerical)
14. Other installment plans (qualitative)
15. Housing (qualitative)
16. Number of existing credits at this bank (numerical)
17. Job (qualitative)
18. Number of people being liable to provide maintenance for (numerical)
19. Telephone (qualitative)
20. Foreign worker (qualitative)
21. Response variable: 1 (bad) or 2 (good)

## Data Cleaning

I didn't need to make a lot of changes, but i did the following:

- Verified if had any null values
- replaced the attributes index for its true meaning for the EDA
- changed the datatypes of the columns to int for the model

## EDA

Some findings of teh EDA:

![image](https://github.com/GabrielRomaoG/Credit-Scoring-Project/assets/98478233/fd742544-29db-404e-94f2-c8bad4d6c2c9)

![image](https://github.com/GabrielRomaoG/Credit-Scoring-Project/assets/98478233/c5803475-8bbe-4ec6-b080-739e19c15e7e)

![image](https://github.com/GabrielRomaoG/Credit-Scoring-Project/assets/98478233/d775ef6b-33c7-4523-83c7-d3cdc0285f31)





