
# Lending club casestudy
## Lending Club Casestdy - Loan Default Risk Analysis


> This project focuses on analyzing loan applications from Lending Club to identify factors contributing to loan defaults. By examining applicant profiles, we aim to uncover patterns that indicate default risk, helping to mitigate credit loss. The analysis addresses the challenge of significant financial losses due to defaults, particularly among 'charged-off' customers. Our objectives include pinpointing key variables that signal default risk and developing actionable insights for better risk assessment. Ultimately, this work seeks to enhance the Lending Club's ability to identify high-risk applicants and improve overall lending strategies.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project involves an exploratory data analysis of Lending Club's loan applications to identify factors influencing loan defaults. By analyzing applicant profiles and historical default patterns, we aim to enhance risk assessment and reduce credit loss for the lending institution.
- The background of this project involves understanding the lending landscape and the financial risks associated with loan defaults. Lending Club, as a consumer finance company, faces challenges in approving loans while managing the potential for credit loss from high-risk applicants. This analysis seeks to leverage data-driven insights to inform better lending decisions and improve the overall risk management strategy.
- The business objective is to identify key driving factors behind loan defaults, understand variables that strongly indicate default risk and develop insights to improve portfolio and risk assessment. Ultimately, the goal is to enhance Lending Club's decision-making process, leading to reduced credit loss and improved lending practices.
- The Lending Club dataset is used containing information about past loan applicants and whether they defaulted or not.


## Technologies Used
- pandas - version 2.2.2
- numpy - version 1.26.4
- matplotlib - version 3.7.1
- seaborn - version 0.13.2
- scikit-learn - version 1.5.2
- scipy - version 1.13.1


## Conclusions
- Higher charged off cases are observed for very high loan amounts. To reduce defaulter cases, the loan amounts are recommended to stay within 17K. Also, not all loans are funded by investors.

- High interest rates on loans is also a driving factor leading to high charge off cases. To curb down defaulter cases, a reasonable interest rate roughly within 5.4% to 11% is recommended.

- Charged Off applicants have slightly higher Debt to Income Ratio significantly higher Revolving Line Utilization indicating they rely too much on loans and consequently cannot pay the debts.Borrowers whose Debt Income Ratio cross 15 and Revolving Line Utilization cross 45 are risky and need to be treated with caution.

- As loan grade increases, from A to G, the charge off rate also increases and the grades are influenced by interest rates. Applicants in small business are taking higher graded higher interest loans, making more inquiries in last 6 months requesting for more credits, struggling with credit repay than debt consolidation and consequently getting charged off more than other purpose categories (about 26%). Lower grade loans preferably grade A should be prioritised.

- While rejecting people taking loans for small business purpose as they had high charge off rates, it should be ensured that no opportunity is missed while rejecting a capable applicant with small business purpose from providing loan by taking care of the nuances. Criteria for applicants taking loans for small business purpose who should not be rejected from taking loans:

    a. Credit score > 0.85
    b. Revolving Line Utilization rate < 35
    c. Annual Income group = VH (16000.00 to 35000.00) 


- Applicants with lower income charge off more.

- Most applicants opt for short term (36 months) loans. Applicants with long term loans (60 months) were observed to have charged off more.

- Charged Off borrowers have lower credit score than fully paid ones. Credit score below 0.8 should be treated with caution.

- Among the states, NE shows highest percentage of charged off applicants. Among employee titles, Walmart employees have higher charge off rates.

- Weak indicators: Although weak indicators, following patterns are observed:

    a. Applicants with higher bankruptcy records have charged off more.
    b. Charged Off applicants have paid higher late fees than fully paid ones.
    c. Among home_ownership categories, 'Other' category applicants comprise the lowest proportion among the applicants but have the highest charge off rate.

## Acknowledgements


## Group Members
Bramhanayaghe Arumugam  (github id : bramhanayaghea)
Anusha Chaudhuri (github id : anusha761)

