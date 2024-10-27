# Project Name
Lending Club case Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refusesto pay or runs away with the money owed.

The main objective is to be able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

Perform an analysis to understand the driving factors (or driver variables) behind loan default, i.e.the variables which are strong indicators of default.
The company can utilise this knowledge for its portfolio and risk assessment.

Using following steps for data processing.

Step 1: Data Cleaning
Step 2: Univariate Analysis
Step 3: Segemented Univariate Analysis
Step 4: Bivaraiate/Multivariate Analysis
Step 5: Results/Conclusion
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions


1. We can say that people with high past record of bankrutcies mostly likely to default
2. There is a high correlation in loan grade percentage for each default ratre 
3. There is a correlation between revolving Utilisation rate vs Loan grade Revolving Utilization and Grade: As the loan grade increases from A to G, the median revolving utilization tends to increase. This suggests that borrowers with (higher grades F,G etc) tend to have higher levels of credit card debt relative to their credit limits.
2. There is a postive  Correlation between Loan amount and Annual income.
3. This shows that most of defaulters are taking smaller loan amounts in range (5000-16000)  and max value is 35000 
4.  There is a high frequency of values at 0 years and 10 years, suggesting that many applicants either have no employment history or have been employed for 10 or more years.
5. Most of defaultors were in low range of annual inc ,this is Negative Correlation 
so this is a strong indicator were 50% of people income is below 60000 
6. From this we can Categorize that as Category class  of total Accounts is increasing the default rate is increasing so the biininghere helped us to bin the customers based on the number of accounts



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Pandas library - version 1.4.2
Numpy library - version 1.21.5
seaborn library 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
