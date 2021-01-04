## Supervised Learning to Predict Customer Churn 

A multinational bank wants to increase its market share in Europe. They've recently noticed that the number of customers using the bank services has declined, and the bank is worried that existing customers have stopped using them as their main bank. 

#### Goal: find out the reasons behind customer churn and predict customer churn

#### Steps: 
- obtain data
- impute missing values
- rename columns and change data types
- obtain the statistical overvieew and correlation plot
- perform exploratory data analysis (EDA)
- perform feature selection using RandomForestClassifier 
- build a logistic regression model
- interpret the data

#### Findings: 
20.37% of customers churned

Those that churned have the following characteristics: 
- higher credit score, average 645.35
- higher balance and estimated salary
- more female customers
- 3-4 products
- age range of 35-45 and as age increases so do chances of churning

Correlations: 
- customer age and churn are positively correlated, 29%
- balance and churn are positively correlated, 12%
- number of products and balance are negatively correlated, 30%

Most important features selected from tree-based features: 
- age
- estimated salary
- credit score
- balance
- number of products

The model build can predict customer churn with 79% accuracy.
