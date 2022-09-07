# Project Name
 You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
 

## Table of Contents
* [General Info](#general-information)
The data given contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

* [Technologies Used](#technologies-used)
1) pandas
2) numpy
3) seaborn
4) matplolib

* [Conclusions](#conclusions)
 1) Customers with interest rates between 13% to 17% are likely to default
 2) Customers with lowest interest rates are the once who likely to payback the loan amount on time.
 3) Customers who are offered the highest interest rates (above 20%) are likely to payback the loan amount on time.
 4) Customers with more credit lines are paying the loan on time. 
    a) This cannot be generalized because there might be a possiblity they take more loans to pay the existing loans.
    b) So the bank should avoid giving credits to the customers who already have lot of credits as they might be scammers.
    c) we have examples of Nirav Modi and Vijay Mallya who used such practices of taking loan from one bank to pay other loan and do money laundering.
 5) The total credit lines also drives the same observation which we made in point no 4) above. 
 6) The customers with annual income of 31k to 58k are likely to become default customers.
 7) The final graph on revolving credit lines also proves that higher the revolving credits higher the chances of the customer defaulting the loans.

* [Acknowledgements](#acknowledgements)
 -Hem Chandra
