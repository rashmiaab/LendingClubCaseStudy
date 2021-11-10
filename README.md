# Lending Club Case Study
> This Case Study is about a **consumer finance company** which has specialization of providing loan for the urban customers. Accordingly when any customer applies for loan, 
> company should be able to decide to which customer it will provide loan based on customer profile. 
> It is understood that decision making is little bit tricky on what basis the this finance company takes the call to provide loan.
> For instance if company rejects loan application of capable customer it will face loss and similarly if it sanction loan to certain customer who will not be able to repay loan.
> Thus below case study speaks about data interpretation of customer profile what features influences in sanctioning loan to them.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Background** : Lending Club Case Study is about a **consumer finance company** which has specialization of providing loan for the urban customers. 
- **Given** : Customer details who have taken loan in past.
- **Business Problem** : Based on dataset related to customers analysis has to be made to helping the finance comapny in decision making to provide loan to urban customers with minimal risk.
- **Data Set Used** : Details of urban customers who have taken loan in the past which comprises of their loan amount, interest rate of loan, long or short loan, annual income, type of home there are staying etc.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Customer with below condition is tend to become defaulter
  - G5 Grade with eight Open Accounts
  - Eight inquiries in last 6 months.
  - Home Ownership status as Other or Mortgage with 10k+ applied loan
  - 2 Bankruptcies with loan amount more than 8k+
  - Very High Salary with 12k+ applied amount.
  - Conclusion 4 from the analysis
 - Customer with below condition are having high profit to business
   - Very low interest rate for all grades except grade A
   - A grade and 60 month term period loan
   - G grade with 60 months term and F Grade with 36 month term.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - pandas as pd
- library - numpy as np
- library - matplotlib.pyplot as plt
- library - seaborn as sns
- library - calendar

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired uPgrad Leaning platform in understaning Exploratory Data Analysis.
- References : https://medium.com/analytics-vidhya/pairplot-visualization-16325cd725e6
- This project was based on https://www.kaggle.com/ekami66/detailed-exploratory-data-analysis-with-python.


## Contact
Created by [@rashmiaab] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
