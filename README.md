# Lending-Club-Case-Study

Problem Statement:
If the customer is likely to repay the loan, then rejecting the loan may lead to business loss
If the customer is not likely to repay the loan, then approving it may lead to financial loss
When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

Identify default applicants using EDA Tools

Analysis:
1) Dropped irrelevant columns
2) renamed the values for few columns
3) replaced null values with mean
4) performed data visualizations using univariate and bi-variate
