# Credit Scoring Project

This project aims to build a custom credit scoring model for a new target audience. It involves analyzing a dataset provided by the client and developing a predictive model to assess creditworthiness.

## Dataset

The dataset contains 1000 records extracted from the client's database. It includes the following attributes:

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

## Project Tasks

1. **Data Exploration**: Perform an exploratory analysis to understand the data distribution and the relationship between attributes and the response variable.
2. **Logistic Regression Model**: Build a logistic regression model to construct a credit score, where a higher score indicates a lower probability of default.
3. **Model Evaluation**: Assess the performance of the logistic regression model using appropriate evaluation metrics.
4. **Alternative Model**: Develop an alternative credit scoring model using Naive Bayes algorithm.
5. **Model Comparison**: Compare the performance of the logistic regression model and the Naive Bayes model, discussing their strengths and limitations.

## Getting Started

To reproduce the project:

1. Download the dataset from [this link](https://archive.ics.uci.edu/ml/machine-learning-databases/statlog/german/german.data).
2. Set up a Python environment with the necessary libraries (Pandas, NumPy, scikit-learn, Matplotlib, Seaborn).
3. Run the provided code in the Jupyter Notebook or any Python environment of your choice.
4. Follow the step-by-step instructions in the code to perform data exploration, build the logistic regression model, evaluate its performance, and develop the Naive Bayes model.
5. Analyze and compare the results obtained from both models.

## Conclusion

This project aims to develop a custom credit scoring model using the provided dataset. Through data exploration, logistic regression, and the Naive Bayes model, we seek to assess creditworthiness for a new target audience. By comparing the performance and discussing the qualities and limitations of each model, we aim to provide valuable insights for credit risk assessment.

For more details, please refer to the code and comments in the Jupyter Notebook or Python scripts.

<<<<<<< HEAD

### The attributes in detail
Attribute 1: (qualitative)
Status of existing checking account
A11 : ... < 0 DM
A12 : 0 <= ... < 200 DM
A13 : ... >= 200 DM / salary assignments for at least 1 year
A14 : no checking account

Attribute 2: (numerical)
Duration in month

Attribute 3: (qualitative)
Credit history
A30 : no credits taken/ all credits paid back duly
A31 : all credits at this bank paid back duly
A32 : existing credits paid back duly till now
A33 : delay in paying off in the past
A34 : critical account/ other credits existing (not at this bank)

Attribute 4: (qualitative)
Purpose
A40 : car (new)
A41 : car (used)
A42 : furniture/equipment
A43 : radio/television
A44 : domestic appliances
A45 : repairs
A46 : education
A47 : (vacation - does not exist?)
A48 : retraining
A49 : business
A410 : others

Attribute 5: (numerical)
Credit amount

Attribute 6: (qualitative) Savings account/bonds
A61 : ... < 100 DM
A62 : 100 <= ... < 500 DM
A63 : 500 <= ... < 1000 DM
A64 : .. >= 1000 DM
A65 : unknown/ no savings account
Attribute 7: (qualitative)
Present employment since
A71 : unemployed
A72 : ... < 1 year
A73 : 1 <= ... < 4 years
A74 : 4 <= ... < 7 years
A75 : .. >= 7 years

Attribute 8: (numerical)
Installment rate in percentage of disposable income

Attribute 9: (qualitative)
Personal status and sex
A91 : male : divorced/separated
A92 : female : divorced/separated/married
A93 : male : single
A94 : male : married/widowed
A95 : female : single

Attribute 10: (qualitative)
Other debtors / guarantors
A101 : none
A102 : co-applicant
A103 : guarantor

Attribute 11: (numerical)
Present residence since

Attribute 12: (qualitative)
Property
A121 : real estate
A122 : if not A121 : building society savings agreement/ life insurance
A123 : if not A121/A122 : car or other, not in attribute 6
A124 : unknown / no property
Attribute 13: (numerical)
Age in years
8

Attribute 14: (qualitative)
Other installment plans
A141 : bank
A142 : stores
A143 : none
Attribute 15: (qualitative)
Housing
A151 : rent
A152 : own
A153 : for free

Attribute 16: (numerical)
Number of existing credits at this bank

Attribute 17: (qualitative)
Job
A171 : unemployed/ unskilled - non-resident
A172 : unskilled - resident
A173 : skilled employee / official
A174 : management/ self-employed/
highly qualified employee/ officer

Attribute 18: (numerical)
Number of people being liable to provide maintenance for

Attribute 19: (qualitative)
Telephone
A191 : none
A192 : yes, registered under the customers name
Attribute 20: (qualitative)
foreign worker
A201 : yes
A202 : no

Attribute 21: (numerical)
response variable
1: bad
2: good

=======
>>>>>>> 61217fc1de5a570297f2420ffae0339b5d30c88e
