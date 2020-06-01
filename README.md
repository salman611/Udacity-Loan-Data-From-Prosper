# Loans Data Exploration

## Dataset

The data consists of information regarding 113,937 loans, each loan has 81 variables, such as Borrower APR,Lender Yield, Debt, etc. [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings
In the exploration, I found that there was a strong negative relationship between borrower APR and Prosper Rating, the borrower APR decreases with the better rating. also borrower APR and Loan Original Amount have negative correlation, when APR decreases the loan amount increases.

Outside of the main variables of interest, Term and Prosper Rating have strong positive relationship with LoanOriginalAmount (when term and rating increase borrower get higher loan amount).I found a
somewhat surprising result, when Loan Term increases the APR increases and that happens with AA, A and B rating. However, in C, D, AND E the APR increases when the term is less. HR rating only borrow at 36 months.

## Key Insights for Presentation

For the presentation, I focus on features that influence the borrower APR, which is the  borrower Prosper Rating,Loan Original Amount, and Loan Term. I start by by introducing the distribution of borrower APR, Loan Term, Loan Original Amount, and Prosper Rating.

Afterwards, I introduced Borrower APR vs. Loan Amount, The Influence of Prosper Rating on relationship between APR and Loan Amount, and Borrower APR across Prosper Rating and Loan Term.