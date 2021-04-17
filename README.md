# Loan Data from Prosper
## by Alex Voigt Quintino Pereira


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) explains the variables in the data set.s


## Summary of Findings

> The dataset has presented two different behaviours regarding the number of new loans from each quarter: it is clear that there is some increase on the number of new loans between Q4 2005 and Q1 2013, but from Q2 2013 to Q1 2014 the quantity of new loans has skyrocketed. Some [news found online](https://www.lendacademy.com/p2p-lenders-2013-loan-volume/) also point to the fact that 2013 was a great year for Prosper.
> Also, the main use appointed by borrowers for the new loans is to pay off other debts. Although it seems to be bad news for Prospers business model, the company seems to do a very good job sorting good payers that are in debt from bad payers that are in debt. As we saw, for the loans that had the `ProsperRating` feature, it presents a normal curve shape around the 'C' grading, indicating that probably Prosper denies borrowers with very bad rating or only allow a certain amount of them into their platform.
> It was also possible to see that most loans are still ongoing and very few of them are past due. The borrowers bankcard credit is also low on its majority, below USD 10k.
> Over time, the new loans were focused on the listing category 'Debt consolidation'. One could think that this fact would be harmful to the business, generating a higher frequency of loans past due. This was not the case, appereantly because Prosper was more strict when admiting new loans, focusing on borrowers with a Credit Grade much more concentrated on grades above C. The BorrowersAPR was also more controled over time when looking at the interquartile range for each quarter. The main relationship though was the estimated return over time: it has got much more refined, meaning less sparse. This is great for the business, because it assures a higher confiability that the investment will be fruitfull for both Prosper and the investors.
> Finally, there's a clear relationship between risk (ProsperRating) and the expected return for each loan. It seems that Prospers AI suggests a BorrowersAPR of more than 20% for when they have a negative expected return, as a way of protecting the mean return.


## Key Insights for Presentation

> Prospers business grew a lot over time, mainly after Q1 2013. 
> Borrowers credit grades and Prospers rating were less sparse over time, showing that Prosper developed good way to control which Borrowers to allow into their marketplace.
