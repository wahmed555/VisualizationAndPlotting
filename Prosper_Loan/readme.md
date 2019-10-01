# (Prosper- Loan)
## by (Praise Onyehanere)


## Dataset

> Prosper is a Fintech company.A place where you can borrow and lend a money. The power to send is limitless. Modern “Fintech companies, as they’ve come to be called, are easing payment processes, reducing fraud, saving users money, promoting financial planning, and ultimately moving a giant industry forward.”

There are 113,937 Loan listing in the dataset with 81 features . Most variables are numeric in nature.
T

## Summary of Findings

> In the exploration, I found that there was a strong relationship between 'creditscoreRange and prosperRating' both parameters have linear relationship. where as there is a strong inverse relationionship between 'BorrowerAPR and ProsperRating'.
while plotting graph between 'Income range vs Count'  I found that the  bulk of the data lies in that lower to middle-income region,such people don't have reserve and savings and I presume such people exploit services such as Prosper’s the most.

'BorrowerAPR count' The bulk of the loans seem to be near the 0.2 mark, which coincides with the credit rating histograms that show that the majority of the users are in the middle of the risk ratings. There is a strange spike in the 0.35-0.37 bin which indicates a strangely popular fee rate for primarily higher risk borrowers. we investigate this deeper in Multivariant section in graph across the 'ProsperRating categories vs borrwer rate' an dfound this to be correct claim.

'credit score' is one of the key indicator of determining a person's paying back their Loans, we visualize the relationship between both 'credit score' and 'Prosper Rating',as we climb the rating categories from 'HR' to 'AA', the credit score of the borrowers also tend to increase.

> outside my main variable of interest i was plotting 'Loan status acros the year 2006 to 2014' in graph to find various Loan status trends but i discovered that largest number of Loans are current this entails that Prosper has shown dramatic growth in recent past.
post 2009 when company's policies changed. 


## Key Insights for Presentation

> For the presentation, I focus on BorrowersAPR, Deliquencies, ProsperRatings, LoanOriginal anount etc. I start by introducing the
borrowers purpose, occupation,Income range , followed by the pattern in BorrowerAPR distribution, Deliquencies count, Loan status spectrum, then  Loan Payment Status vs Time (2006 to 2014) plot,

I used box plot to understand the relationship among "borrower’s 'Prosper rating' and their 'Credit score'".

I draw scatter plots to understand the relationship among "BorrowerAPR Vs DebtoIncomeRation Vs ProsperRating
" amd relationship among "'Debt to Income Ratio' vs 'credit score Range ' vs 'Defaulter ' vs 'Completed Loans'"