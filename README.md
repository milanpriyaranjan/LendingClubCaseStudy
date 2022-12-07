# Lending Club Case Study
> Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contributors](#contributors)



## General Information
A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss).

The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.

For this poject we will use Loan Data Set (loan.csv).
Below is a quick look at the data that is present in the Data Set.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

- Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

- Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

- Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Conclusions
- A combination of High loan amount, interest rate and larger term is a leading factor of Loan Defaults.
- Loans taken for the purpose of Small Business is also a leading factor for Defaults.
- Annual income of the applicant also plays an important role in factors leading to Loan Default.
- Conclusion 4 from the analysis


## Technologies Used
- Python - version 3.x
- Jupyter Notebook 6.4.12 (anaconda3)

## Libraries Used
- Pandas , Numpy , Matplotlib , Seaborn


## Contributors
Created by @milanpriyaranjan and Chaitnya Gadela- feel free to contact me!