Summary observations from EDA:

Majority of the customers are female customers and also most of the customers are Single.
​
• There are customers who are making advance payments which is indicated by the negative value in the Bill Amount field indicating these are credible customers.
​
• Most of the defaulters are of < 60 years of age

Risk is higher for customers who have not done repayment for 2 months or more. For repayment status of -2, -1 and 0 we see the risk is quite low

From the plot we see that there are not many defaulters with age > 60 years. Major chunk of defaulters are young

Risk is also not high for customer with age > 60

As we are checking the repayment status of Sep, there seems to be very few customers with high risk and not done repayment for more than 5 months

Most of the high risk customers are defaulters

# #Clarification to the assumptions or intuitions we had before EDA:
• Are customers with a higher ‘LIMIT_BAL’ tending towards non credibility? They have a higher credit limit and are spending accordingly. However, when it comes to repayment maybe they are not able to pay back -> RISK_VALUE shows negative correlation with LIMIT_BAL indicating that higher risk may be associated with customers who have a lower credit balance -> We see that median value of the LIMIT_BAL for defaulters is less compared to that of non-defaulters

• Are customers with lower education levels, earning less and not able to pay back the bill and hence tending towards default/non-credibility -> Out of 22% of customers who have defaulted, 11% are University Graduates. So our assumption of lower educated customers being a problem is not very true

• Are young customers taking undue advantage of the credit limit, spending lavishly but not paying back -> There is no difference in median age between defaulters and non-defaulters

• Are married customers becoming non credible due to increased responsibility of family. -> There is no major difference between default count of Single and Married customers

In all months we see maximum number of customers with '0' repayment status which indicates that most of the customers are using revolving credit. Also, for the month of Sep we observed that even the due amount is highest for this group. This is the group of customers where majority of the company’s amount has to be recovered. We also observe that not many customers are utilizing the credit beyond the specified limit hence not getting called out.
​
-> Action: For the customers who are using revolving credit and have a bill amount tending to breach the credit limit over past 3 months, company can cross sell and provide options of fixed repayment or EMI or loan bat competitive interest rate so that the customer does not tend towards default status
​
• As on Sep around 9% of the customers are not using the credit facility.
​
-> Action: Potential customers who can be pitched in with offers for credit card sale
​
• The number of customers who have defaulted for more than 3 months is low but the due amount/customer is higher which is a concern.
​
-> Action: Recovery measures to be initiated for these customers
