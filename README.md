# Lending Club Case Study [Course 1: Statistics, Module 8]
 
## Problem Statement

You work for a consumer finance company specializing in offering various types of loans to urban customers. When the company receives a loan application, it must decide whether to approve the loan based on the applicant’s profile. There are two types of risks associated with this decision:
1. If the applicant is likely to repay the loan, not approving it results in a loss of business for the company.
2. If the applicant is unlikely to repay the loan and is likely to default, approving it may lead to a financial loss for the company.

## Case Study Objective

Utilize Exploratory Data Analysis (EDA) to examine how consumer and loan attributes impact the likelihood of default.

## Impediments & Constraints

When a person applies for a loan, the company can make two types of decisions:

1. Loan Accepted: If the company approves the loan, there are three possible outcomes:
    - Fully Paid: The applicant has fully repaid the loan, including the principal and interest.
    - Current: The applicant is currently making payments, and the loan tenure has not yet ended. These applicants are not labeled as 'defaulted.'
    - Charged-Off: The applicant has failed to make payments for an extended period, resulting in default on the loan.

2. Loan Rejected: The company rejects the loan application if the applicant does not meet the required criteria. Since these loans were not approved, there is no transactional history for these applicants with the company, and thus, this data is not available in the dataset.

## Summary
 Below files are included as part of the case study:
 
 1. Akshaay_Vijay.ipynb: This is the ipython file where EDA for this case study was performed.
 2. Akshaay_Vijay.pdf: Presentation about the case study analysis and Conclusions of the EDA performed.
 3. README.md: Describes the problem statement and its objective.
