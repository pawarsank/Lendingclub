## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
# Lending Club Case study
**background Information**
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

1 Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

1.1Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

1.2.Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

1.3.Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

2.Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

**Business Problem Statement**
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

**Dataset being used**
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

Recommendations to offer more loans to increase business.

1. Offer High income borrowers with competitive interest rate for loan category of  Debt consolidation, car, wedding. 
    as they have higher chances of repayment.

2. Customer with high income (60000+) have good records of replaying full loans.    
     
    We recommend to attract more customers with high income (60000+) with competitive interest rate to increase   
    business.
  
3. Target Customer with lesser revolving credit utilization as they have high chances of loan repayment. 

![image](https://user-images.githubusercontent.com/108537520/183948698-3bde642c-4bc3-4c51-9262-aa8a75e2bfdf.png)

Recommendations to avoid defaulting loans to restrict loss.

1. Avoid loan for purpose of Small Business as they have high chances of default. 
  
2. Avoid loan or charge higher interest rate to borrower having more public derogatory records as they have higher 
   chances of defaults. 
  
3. Reduce loan amount to borrowers having less income.( income < 40000) or higher DTI. 
  
4. Reduce loan amount to borrowers having high utilization of revolving credit. 
![image](https://user-images.githubusercontent.com/108537520/183949152-4ac9ddfb-deeb-4c87-a124-8100506219de.png)


## Technologies Used
- Python Pandas
- Python Numpy
- Python visualization - matplotlib & Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This case study is authered by Sanket Pawar & Pritam Narkar.


## Contact
Created by [@pawarsank] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
