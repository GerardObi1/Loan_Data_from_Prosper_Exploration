# Loan Data from Prosper Exploration


## by Gerard Nonso Obiora


## Dataset
The dataset contains 113,937 loans with 81 features on each loan including loan amount, borrower rate (or interest rate), current loan status, borrower annual percentage rate, borrower income, and many others. 


## Summary of Findings
Investigation into the dataset shows that borrower loans had APR between less of 0.1 and a little greater than 0.4. Most of the borrowers were gainfully employed with a fairly large number of them having full time employment. Then, about less than 10000 of them respectively were spread across other categories namely: self-employed, retired, not employed, engaged in a part-time employment, status of employment not stated and others. The most reoccurring employment duration was 4 days.

Then, most of the borrowers were given a 3-year period to repay the given loan. Notably is that between 1 to 5 years was given to repay the loans and loan amount of 4000 was mostly given out.

Furthermore, borrowerAPR and loan original amount, stated monthly income and borrower rate, stated monthly income and borrower APR, borrower rate and loan original amount, were negatively correlated pairwise respectively. On the other hand, borrower APR and borrower rate, stated monthly income and loan original amount, were positively correlated pairwise.

Also, the exploration showed that loan original amount increases with increase in loan term. And, the loan original amount of those self-employed and employed were greater than those of not available, full-time, others, not employed, part-time and retired. While those of full-time and others was in turn greater than those of not employed, part-time and retired.

Borrower APR and borrower rate of Not employed and others were more than the rest of the employment status categories. Term had no effect either on borrowerAPR nor original loan amount when plotted alongside them.

## Key Insights for Presentation

The exploration was carried out to ascertain the feature(s) that can affect BorrowerAPR (Annual Percentage Rate) for a loan. I started by looking at the BorrowerAPR feature visually. And then moved on to make a plot of: 
 - the numerical variables and
 - term and loanoriginalamount features against borrowerAPR.
