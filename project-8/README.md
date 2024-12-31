# Supervised Learning: Beta Bank

## Introduction
[Project Notebook](https://github.com/reondaze-a/tripleten-projects/blob/main/project-8/betabank.ipynb)

In this project I will be working with Beta Bank. Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.

## Goal
I need to predict whether a customer will leave the bank soon. I have been provided with the data on clients’ past behavior and termination of contracts with the bank. My goal is to build a model with the best possible *F1* Score.

## Data Description
Features:
- `RowNumber` — data string index
- `CustomerId` — unique customer identifier
- `Surname` — surname
- `CreditScore` — credit score
- `Geography` — country of residence
- `Gender` — gender
- `Age` — age
- `Tenure` — period of maturation for a customer’s fixed deposit (years)
- `Balance` — account balance
- `NumOfProducts` — number of banking products used by the customer
- `HasCrCard` — customer has a credit card
- `IsActiveMember` — customer’s activeness
- `EstimatedSalary` — estimated salary

Target:
- `Exited` — сustomer has left

## Libraries
- Pandas
- Numpy
- Scikit-learn
