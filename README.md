# (Dataset Exploration Title)
## by (your name here)


## Dataset

The dataset consisted of borrower APRs and attributes of 113,937 loans. The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc. The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000) with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).




## Summary of Findings

In the exploration, I found that the borrower APR is negatively correlated with original loan amount. The borrower APR also decreases with the increasingly better rating. From poor to better ratings, borrowers with ratings of HR have a high APR with the lowest amount in terms of loan amount. This is followed by E, D, C, B, A and AA respectively. This is true because borrowers with poor ratings tend to have high interest rate or APR with little accessibility to loan facilities where as borrowers with better ratings tend to have low interest rate or APR with better accessibility to loan facilities.

I further examined the borrower APR against loan amount by looking at the effect of the Prosper rating. This showed that with better Prosper ratings from HR through to AA, the relationship between borrower APR and loan amount changes from negative to slightly positive. I further looked the rating and term effects on loan amount which showed that as and when the ratings improved, the loan amount amongst all the categories of term increases significantly.

The comparison of Loan Amount and Monthly Income in terms of the effect of Term shows an indication that Term has a significant impact on loan amount and rating where as there is no signifcant impact on monthly income and rating. As and when the ratings improve, the loan amount amongst all the categories of term increases significantly.


## Key Insights for Presentation

For the presentation, I focused on the loan characteristics that could affect the borrower APR, which are loan amount and Prosper rating. I started by showing the distribution of borrower APR, followed by loan amount variable. 

Afterwards, I ploted a matrix of the numeric features against the categorical features and then introduced each of the categorical variables.

Then, I showed the relationship between APR vs. loan amount. I also examined the effect of rating on ralationship between APR and loan amount.