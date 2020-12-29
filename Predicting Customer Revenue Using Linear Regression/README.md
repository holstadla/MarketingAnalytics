## Building a Linear Model to Predict Customer Spend  

#### About the Data
The original Excel datafile contains the following information:
- Invoice number
- Stock code
- Quantity
- Invoice date (years 2010 and 2011)
- Unit price
- Customer ID
- Country

#### Creating Features for Transaction Data
Goal: prepare this data for a regression of customer transaction data from 2010 against the spend for 2011. 

Must create features from the data for the year 2010 and compute the target (amount of money spent) for 2011. 

#### Building a Linear Model Predicting Customer Spend
Goal: build a linear model on customer spend using the features created.

Predict 2011 revenue of a customer with the following data: 
- 2010 revenue = $1,000
- number of days since last purchase = 20
- number of purchases = 2
- average order cost = $50

## Building a Regression Model to Predict Storefront Location Revenue

#### About the Data
Provided the data on a store's revenue as well as important factors regarding the surrounding area at various locations, including number of competitors, median income, number of loyalty members, population density, and location age. 

Goal: build a regression model to predict storefront location revenue based on information about the area the storefront is located in. 

The model should be able to: 
1. describe the relationship between revenue and factors related to the storefront's location 
2. predict the revenue of a store based on its location and age

Predict the revenue of a location with the following data: 
- location has 3 competitors
- median income of $30,000
- 1,200 loyalty members
- population density of 2,000
- location age of 10
