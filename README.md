# Credit-Scoring
This is a training project aimed at exploring different machine learning methods for solving credit scoring problems. - https://www.kaggle.com/competitions/cmf-2022-bank-scoring-case/overview

## Introduction
The task of credit scoring is one of the most popular areas where machine learning algorithms are applied. The scoring program is developed by risk managers of the bank based on a large amount of data on repayment/non-repayment of individual loans.
High-quality scoring model allows to make decision-making on a flow, to reduce disbursement terms and to simplify collection of necessary documents. For the bank's client the use of scoring reduces the cost of granting and the loan itself, significantly reduces the list of documents required by the bank and the terms of granting.

## Historical data

In this problem we are given historical data: a set of 10 attributes on loan applications. For each application you know if the loan was overdue (target=1) or if it was repaid on time (target=0).
age — borrower's age

monthly_income — borrower's monthly income

credit_card_utilization — the ratio of the account balance to the credit limit

debt_to_income — debt to income ratio

credits_loans — current number of loans and credit lines

mortgage_loans — current number of mortgage loans

family_members — number of members in the borrower's family

overdue_30_59_days — number of previous delinquencies from 30 to 59 days

overdue_60_89_days — Number of previous delinquencies from 60 to 89 days

overdue__more_than_90_days — the number of previous delinquencies of more than 90 days

target — whether the loan was overdue for more than 90 days - only available in the training sample The y_train file contains answers whether or not the loan was overdue (0 or 1) in fact

## Solution
The process of solving that problem is presented in the notebook "Final.ipynb"

## Presentation
My team and I created a special presentation "scoring cmf.pptx", combining our best decisions, analytics and visualization of the data and suitable machine learning algorythms and their  evaluations.
