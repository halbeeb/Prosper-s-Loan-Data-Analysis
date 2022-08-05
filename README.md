# (Loan's Data Analysis)

## by Habeeb Adewale Abdulrasaq


## Dataset

> In conducting this analysis, loan dataset from Prosper was used. This loan dataset has 113,937 loan observations and 81 columns/fields which include interest rate, lender yeild, borrower's income, loan close date, credit rating, borrower's occupation, estimated loss, loan tenure, investors and many other field names.

> Given a large number of columns, this dataset was subset to include loan amount,borrower APR, borrower rate, occupation, monthly income, loan tenure, rating, employment status, closed date, home owner and lender yield. This dataframe was used for the exploratory analysis, but this exploration there were wrangling steps that were performed to assess and cleaned for its tidiness and messiness.

> The data wrangling performed are imputing the missing values for the columns, convert closeddate to datetime data type, change true and false of isborrowerhomeowner to home owner and non home owner, and feature-engineer of borrower's APR and borrower's rating to borrower's cost (rate)


## Summary of Findings

> > Our variable of interest which is borrowing cost has a strong relationship withlender's yield, moderately weak but relationship with original loan amount. And barely no relationship or association with term. A rating of Prosper equally that depict that the higher loan's term for the rating, the probable high cost of borrowing cost and this B and D ratings, while other rating rating categories varying and inorder borrowing cost across the loan's term. Although as observed in the figure above, AA has lowest borrower's cost (rate) for loan's term of 12, 36 and 60 respectively for lowest cost, lower and low cost of borrowing.

> The C rating show that borrowing cost might not change for any amount of loan sought and the same thing for A, D, and B ratings. Only E, AA and HR that have a slight possible change in borrowing cost with respect to loan amount request. While it seems that majority that sought it mostly go for 5,000. And as this can be seen above, there is negative but weak relationship between loan amount and borrower's cost. For the relationship between Prosper's rating and loan amount sought, as expected better ratings tend to go for higher loan's terms such as 36 and 60 months and the ratings that are not good as them tend to go for lower amount for 36 and 60-month terms. This is evident in loan original amount and prosper rating (Alpha).

> Nonetheless, or the relationship between monthly income and rating as seen above, having a better rating does not imply that one's monthly income is higher. Those whose stated monthly income is more than 12,000 seem to have a D rating and 12-month term. And it is equally observed from the data most people that do go for 12-month term have higher income - And this make sense in a wway higher income would be able to pay off the loan as soon as possible. As there appears most loan seekers went for this and the negative but moderately relationship was inferred. Most loan seeks go for loan amount between 5,000 and 25,000 unlike lower terms. For the term of 60 months, the slope of loan amount with respect to borrower's cost is steeper the remaining two and this show there is negative relationship between the two and most loan seeks go for loan amount between 5,000 and 25,000 unlike those with 12 months term.


## Key Insights for Presentation

> As we have it in the explanatory analysis, the key insights are:

> The borrowing cost histogram is multimodal as the borrowing cost are most evident between 0.05 and 0.385.

> 36-month loan term is more than the double of the other two loan term (10 and 60 months) combined in terms of loan seekers' preferences

> The number of status of employed credit consumer is more than the number of other employment status conbimed.

> Borrowing cost has a negative yet fairly weak association with loan and extremely weak and negative connection with monthly income as it has barely zero relationship with term and a very stong positive relationship with lender yield.

> The relationship between borrowing cost and stated monthly income implies that monthly income increases the borrowing cost would fall.

> For the term of 12 months, there is negative but weak relationship between loan amount and borrower's cost. For the term of 36 months, there appears to be negative but moderately relationship; and the term of 60 months, the slope show there is strong negative relationship.

> AA has lowest borrower's cost (rate) for loan's term of 12, 36 and 60 respectively for lowest cost, lower and low cost of borrowing.and A rating of Prosper equally that depict that the higher loan's term for the rating, the probable high cost of borrowing cost for B & D ratings