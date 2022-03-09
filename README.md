# Lending Club Data Analytics Case Study
Lending club data analytics case study is a fictious case study about a lending club which facilitates loan provisioning and mainteanance. This project contains a `jupyter` notebook file containing all the analytical functions perfomed on the dataset (represented by `loan.csv`).

## Table of Contents
* [Background](#background)
    * [Important Aspects of the Dataset](#imprtant-aspect-)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Background
This case-study is an academic analysis of a fictious Finance house / Lending House known as Lending Club which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

### Important Aspects of the Dataset
- Data set contains all loans processed by the Lending house
- When a person applies for a loan, there are two types of decisions that could be taken by the company:
  - **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:
    - **Fully Paid**: Applicant fully paid his loan
    - **Current**: Existing Loan and customer is paying the instalments.
    - **Charged-off**: Customer have defaulted to the loan
  - **Load Rejected**: Customer's loan have been rejected


## Conclusions
### Trend Analysis
- Number of charged offloans is more then number of current, underprocess loans
- Not much diffrence between long-term vs short term loans 
- People having more the 10 years of experience have more loans
- In `2011` maximum number of loans where issued
- Averge loan amount lies between 10K to 15K
- 75% of loans are amounted above 12K to 18K (approx)
- More customers are taking loan for `debt consolidation`
### Multi-variate
- There is a Positive correlation between annual income and employment years
- Loan amount, investor amount, funding amount are strongly correlated.
- Annual income with DTI(Debt-to-income ratio) is negatively correalted.
#### Intrest Rate vs Charged Off
- There is a direct relation of charged-off loan with higher interest rates
- Loans with higher interst rates are more riskier
#### Home Ownership vs Loan Status
- Number of applicants having rented house is high
- Charged-off loans having rented house is high as well
#### Purpose of Payments and Charged Off
- More numbre of people are doing debt consolidation, that is why the charged off is high as well
- Credit card, other and Small business have high charged-off's number as well
#### Determining Relationship of Employement Lenght
- People with 10+ years of experience have more charged off as they have more number of loans
- People having no experience have high number of charged-off
#### Relationship of Annual Income
- People having annual income between 20K to 60K have more number of charged-offs


## Technologies Used
- pandas
- numpy
- warnings
- seaborn
- matplotlib
- matplotlib
- datetime

## Directory Structure
```
.
├── LICENSE
├── loan.csv
├── Muhammad_Furqan.ipynb
└── README.md
```

## Acknowledgements
- https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html
- https://seaborn.pydata.org/#:~:text=Seaborn%20is%20a%20Python%20data,introductory%20notes%20or%20the%20paper.


## Contact
Created by [@furqanbaqai] - feel free to contact me!