# Overview-Analysis-Towards-Loan-Customer
### Project Overview
In this project, we will explore the characteristic traits of approved loan customers. We will look for any traits that have a dominant effect on whether a customer's loan is approved. At the end of the exploratory data analysis, we will create a dashboard with spider charts to showcase the differences between approved and rejected customers.

The objective of this notebook is to understand how a loan company chooses which customers are eligible for a loan. We will also determine which features are most important in the machine learning algorithm.
### Data
The data was obtained by academic competition and has been uploaded as `lion-loan-train.csv`
### Methodology
- Preprocessing: making sure all the missing data was taken care of and handling outliers
- Exploratory data: find the correlation relevant data by chart visualization
- Feature engineering: using random forest machine lerning to compare the feature selection
### Result and Evaluation
- The high income of the applicant and coapplicant, if any, is not the main factor for getting a loan. However, it is known that the minimum income figure for obtaining a loan is 5446.
- Credit history is the most significant factor in the acceptance of a loan. This may be due to knowledge of the individual's characteristics regarding previous loans.
- The loan amount above the average of 149 is likely to be rejected. This can be seen in individuals living in rural areas, who tend to borrow above the average.
- Gender does not have a major impact on loans, but married, self-employed, and education have a slight impact on loan acceptance. Individuals who are married, self-employed, and graduates tend to borrow above the average loan amount.
- Dependents with 0 and 2 have a lower loan value than others.

According to the exploratory data analysis, the most dominant trait is credit history, followed by income and dependents. More than 70% of people with good credit history are approved for loans. However, the random forest machine learning model shows different results, as we can see below.
![image](https://github.com/andreetanjung/Overview-Analysis-Towards-Loan-Customer/assets/123824152/8df6dd20-ae54-475a-95f6-7ea974d43beb)

### Project Insight on Real Life Business
The average income and loan amount are not significantly different between loan status Yes and No at first glance. However, the average value determines which one passes and which one does not. In the business world, of course, what we can measure is numerically, and these insignificant differences will certainly have a significant impact on the company's profit if the number of customers is large.
### Directory Structure and Brief Description of Files
`Hacktiv8 Talent Fair 2023.ipynb` is a Jupyter notebook that contains the complete project code, including data pre-processing, feature engineering, and evaluation.
### Tableau Dashboard
Link dashboard: https://public.tableau.com/app/profile/andrian5182/viz/EligibleLoanDashboard/Dashboard1?publish=yes
