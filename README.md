# Lending Club-Case study
> Risk analysis for a finance company where we would like to help company in order to take decisions to offer loan to a particular applicant or not. Essentially, risks are identified based on the applicant's profile.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Risk analytics of banking and financial services and analyze the data to minimise the risk of losing money while lending to customers.
- You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:   
    * If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
    * If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
- This project is a Data Exploration project and tries to find as much findings as possible without the use of any Machine Learning and just simple plain EDA and Data Visualization.
- The analysis and visualizations in the notebook are self-explanatory in order to decide the driving factors for a new loan 
- In the dataset used, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. 

## Conclusions
- When the loan application states that the purpose of loan is debt consolidation and small business, verify/evaluate the applicant thoroughly as it has high tendency to default.
- Loans having higher interest rate have more defaulters. Hence, do a thorough background verification of the applicant in such cases.
- Low grade loans have high tendency to default. It shows that grading system to analyze the defaulters is working as expected. Keep categorizing them as it helps in finding probability of defaulting.
- Lower and mid range customers tend to default. Lending club should be more conscious  when providing loan in such cases.
- Before approving loan, lending club should take a look at the DTI(Debt to Income Ratio) of the applicants, as higher the DTI, higher the tendency of defaulting.
- Lending club should evaluate the customers who stay in a rented place as they tend to have higher defaulting rate.

## Technologies Used
- python library - version 3.9.7
- numpy library - version 1.20.3
- pandas library - version 1.3.4
- matplotlib library - version 3.4.3
- seaborn library - version 0.11.2
- jupyter notebook - server version 6.4.5

## Acknowledgements
Give credit here.
- This project was inspired by Lending Club case study
- This project was based on [Lending Club](https://www.lendingclub.com/).


## Contact
Created by [@pradeeproy303] - feel free to contact me!


 ## License
This project is open source.
