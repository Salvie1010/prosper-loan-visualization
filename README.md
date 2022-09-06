# (Prosper Loan Data Exploration)
## by (Salvage Ajibade)


## Prosper Loan Dataset


The data consisted of borrower information and attributes for 113,937 loans. The attributes included CreditGrade, LoanStatus,occupation,employment status, borrower state, EmploymentStatusDuration,IsBorrowerHomeowner, IncomeRange, CreditScoreRangeLower, CreditScoreRangeUpper, BorroweRate and  70 other variables. Only 15 variables were investigated and explored. From the selected features, i created new variables such as : Credit Sore, Income and occupational classes(a group of sectors of occupations). I also focused on only 6 states in the dataset.



## Summary of Findings

After the exploration, i discovered that the  reasons that lead to loan default/charge offs (delinquency) are High borrower rates and debt to income ratio, very low credit scores and income (or unemployment). 

At first, the Debt to income ratios didnt really correlate with the income in the heatmap but after creating a scatter plot, i discovered a trend between income and debt to income ratio. It was that most borrowers with more than $5,000 income had a very low debt to income ratio while the ones earning less than $5,000 (especially $0)  had varying debt to income ratios(with most of them ranging from 0 to 6). 

The occupations also didn't really affect the reasons for borrowing loans as much as location of borrowers did. For example: sales workers took more student loans than students.Executives took the highest number of loans for auto  and Students took more loans for other reasons than student loans. On the other hand, there was a very high number of loans for boats in Florida (due to the fact that florida has alot of water bodies) and most loans in Georgia  were for Debt consolidation.

Despite Georgia having the smallest popultion in the dataset, It had the 3rd highest number of unemployed borrowers but least number of part time workers(these are the two classes that earn the least). The Credit scores of the defaulters were mostly below 100 while the borrower rates were headed towards 0.25.Since, most borrowers from Georgia had one of the highest borrower rates and smallest credit scores leading to the highest default rate.



## Key Insights for Presentation




For the presentation, I focused on just six of the 15 variables I investigated and left out most of the intermediate derivations.

I started by introducing the main variable, Loan Status to visualize its disribution, followed by Income and Borrower State. After this, I used a scatter plot to see the relationship between Credit score and borrower rate, and bar plots to compare other numerical and categorical data in: Debt to income ratio by state , loan status & income. To visualize data like BorrowerRates & Loan Status in different States, I used a heatmap. I also removed certain visualizations (Credit Grade by Debt to income ratio barplot) from my subplots to emphasize my variables of interest. 
