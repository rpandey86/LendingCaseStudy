# Lending Club Case Study
> Lending Club Case Study analysis using EDA


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
This project performs EDA on lending data provided and find driving factors which are useful loan application approval and processing.
- What is the background of your project?
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile. Two types of risks are associated with the bank's decision:

-   If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

-   If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given below contains information about past loan applicants and whether they 'defaulted' or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
When a person applies for a loan, there are two types of decisions that could be taken by the company:

1.  Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

    -   Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

    -   Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

    -   Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

2.  Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
- What is the business probem that your project is trying to solve?
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to 'risky' applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.
- What is the dataset that is being used?
for this project `loans.csv` dataset is being used.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Driving factors for loan approval from the analysis
The best driving features for the Loan default analysis are: 
<ul>
<li>term
<li>grade
<li>purpose
<li>revol_util
<li>int_rate
<li>installment
<li>annual_inc
<li>funded_amnt_inv
</ul>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python          3.9.6
- numpy           1.26.4
- seaborn         0.13.2
- matplotlib      3.8.4
- ipython         8.18.1
- pandas          2.2.1
- jupyter_client  8.6.1
- jupyter_core    5.7.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Team
Sagarika Bhuyan (@SagarikaBh)
Rohit Pandey 


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
