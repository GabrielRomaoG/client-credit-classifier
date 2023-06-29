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


## Getting Started

To reproduce the project:

1. Set up a Python environment with the necessary libraries (Pandas, NumPy, scikit-learn, Matplotlib, Seaborn).
2. Run the provided code in the Jupyter Notebook or any Python environment of your choice.
3. Follow the step-by-step instructions in the code to perform data exploration, build the logistic regression model, evaluate its performance, and develop the Naive Bayes model.
4. Analyze and compare the results obtained from both models.

## Conclusion

This project aims to develop a custom credit scoring model using the provided dataset. Through data exploration, logistic regression, and the Naive Bayes model, we seek to assess creditworthiness for a new target audience. By comparing the performance and discussing the qualities and limitations of each model, we aim to provide valuable insights for credit risk assessment.

For more details, please refer to the code and comments in the Jupyter Notebook or Python scripts.
