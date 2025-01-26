# Lending Club Case Study
> Identify the driving factor for loan getting defaulted which company can use it for portfolio and risk management.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

## General Information
- **About company**: A consumer finance company which specialises in lending various types of loans to urban customers. Borrowers can easily access lower interest rate loans through a fast online interface. 

- **Context**: Lending loans to ‘risky’ applicants is the largest source of financial/credit  loss. Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed

- **Business Problem**: Identify the driving factor for loan getting defaulted which company can use it for portfolio and risk management.

- **Dataset**: The Dataset provided has two set of attributes i.e Consumer Attributes and Loan Attributes that influence the tendency of loan default.


## Conclusions
A. **Bivariante analysis**:
* Loan default increases as loan amount goes high.
* Default loan increases in proportion to increase in interest rate
* The default case decreases as the annual income increase.
* Small_business loan purpose has high number of default cases, followed by renewable_energy purpose
* The effect of grade to default loan cases increase when grade moves from A to G
* Emp Length 0 years contributes more to default case.
* 'NV', 'FL' and 'CA' addr state has more number of default loan case compared with total loan application
As delinq_2yrs goes beyond 0, the default chance increases

B. **Multivariante Analysis**:
* Applicants with Low annual income (-0.07), Low grades (0.15), a history of delinquency are more likely to default.
* Offering a high-interest rate (0.92) to applicants with low grades increases the likelihood of default.

## Technologies Used
- Python - version 3.12.7
- Numpy  - version 2.2.1
- Pandas  - version 2.2.3
- MatPlotLib - version 3.10.0
- Seaborn - version 0.13.2

## Contact
Created by [@chidambaram0705] - feel free to contact me!
