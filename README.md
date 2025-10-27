Does the linear regression model (ie. y=mx + b) make sense when X,Y coordinates are entered?

Yes, the linear model makes sense as a starting point because it captures a direct trend between customer activity and spending. However, it doesn't explain 100% of the data, so there are nonlinear factors that the model doesn't capture.

What does the slope of the regression line indicate about the relationship between transaction count and spending?

Holding everything else constant, if the customer makes one more transaction in the last 12 months, the total estimated spending increases by about $115.

What insights can the bank gain about customer engagement and spending patterns?

The bank can use this model to prioritize highly active customers and allocate more benefits to those with high spending potential. It can also detect declining usage among older customers and launch retention campaigns before losing them.

Insights:

Target: Total_Trans_Amt (total annual card spending).

Features used: Total_Trans_Ct, Credit_Limit, Customer_Age, Months_on_book.

The dataset is clean (no nulls or duplicates).

The histogram shows that most customers have medium/low spending and few have extremely high spending.

The linear regression model achieves R² ≈ 0.66, meaning that ~66% of the spending variation can be explained with just four simple variables.

The most important variable is Total_Trans_Ct: more transactions ⇒ more spending.

Business insight: The bank must encourage frequent card use to increase revenue.

