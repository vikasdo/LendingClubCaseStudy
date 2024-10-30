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

Key High-Risk Indicators:
Factors such as loan grades, loan amounts, low annual income, loan term (in months), and revolving balance utilization play crucial roles in determining the likelihood of default.
Insights for Prevention:
Impact of Loan Grade: There is a noticeable trend where lower loan grades (from A to G) correlate with higher default rates. Adjusting the terms for these lower grades may help reduce associated risks.
Revolving Utilization Rate: Higher revolving utilization rates are commonly found in lower grades, such as F and G. This highlights the need for more thorough credit evaluations for individuals with significant credit card debt ratios.
Correlation Between Loan Amount and Income: While higher income often permits larger loans, defaults are frequently observed among those with lower income levels. Confirming income can improve the precision of loan approvals and assessments of repayment ability.
Bankruptcy History: A previous bankruptcy is significantly associated with increased default risks, making it vital to track bankruptcy records for effective risk assessment.
Additionally, there is a relationship between low annual income and elevated default rates, underscoring the importance of setting income thresholds during loan evaluations.
Lastly, an increase in the total number of accounts is correlated with a higher likelihood of default, stressing the necessity for tailored risk assessments.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Pandas library - version 1.4.2
Numpy library - version 1.21.5
seaborn library 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on few of the EDA techniques researched online.


## Contributors
Donthula Vikas and Gunupudi Lakshman

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
