# Loan Data Exploration & Visualization
## by Michael J. Summers

## Dataset
The data set contains information about loan information by Prosper. 

It can be found here:
https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv

There is also a data dictionary to explain the dataset’s variables, which can be found here:
https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

This was a large data set 81 columns by 113937 rows. It contained a lot of information I determined were unnecesary for my analysis. As part of the cleaning process, I dropped several columns. I also had to change few column names as well as datatypes.

Afterwards I saved the cleaned data as a .csv file. Final shape was 34 columns and 113937 rows of data.

## Summary of Findings

I found most loan seekers preferred or qualified for the 36 month term by a large number. 
I found the largest group by income range was 25k to 49.9k of annual income. Followed by 50k to 74.9k. 
I explored CreditGrade and visualized that “C” rating was the majority count of loan applicants in this dataset.
I thought it interesting to explore employment status and saw that a few “Retired” applicants were in this dataset.
Utilized histograms to analysis the distribution of monthly income, revolving credit balance and monthly loan payments.
Then, charted average loans by Occupation, Income Range and Employment Status.
Credit Grade, Borrower’s APR and Rate where explored in several charts and queries. Debt to income ratio, Prosper Score, Estimated Loss and Estimated Effective Yield where a few more variables charted to determine correlation.

## Key Insights for Presentation

The main feature of interest is Occupation and what is the average loan amount by profession. 
Additional features of interest are to identify groups by Income Range, Credit Grade and or Employment Status. I want to see which of these groups are in the majority in this data set. This could be useful information to a banking organization to determine potential clients to target based on the data from this set. We can determine the average Income Range of an applicant and market specific loans that fit their needs and budgets.

To conclude, the data set featured loan applicant data. I explored several variables and compared the more interesting variables by Income Range of the applicants. I performed some bivariate exploration to discover trends in Employment Status by Term of loans. As well as, in category of Credit Grade. Then, I explored Credit Grade by Income Range. My inquiries revealed trends for the 25k to 49.9k to be the larger group on loan applicants in this data set. I ended my analysis with box plots on Income Range and Borrower APR and Loan Amount.

Originally, I sought to identify the average loan amount by occupation. As I dive deeper in my analysis, I sought to narrow the categories down to employment status and income range. 
Listing by income range would be a more general category and it is a major factor for loan applicants. 
This could be used as a baseline for what loan amount an applicant may qualify for.




