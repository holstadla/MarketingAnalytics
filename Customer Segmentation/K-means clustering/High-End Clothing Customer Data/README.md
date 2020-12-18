## High-End Clothing Customer Data for Target Marketing

 A high-end clothing company has collected customer data, including age, income, annual spend at the store, and number of days since their last purchase. The company wants to start target marketing campaigns, but doesn't know how many different types of customers they have or who they really are. Therefore, the company wants the customer population segmented based on the data gathered and wants to know how many customre clusters there are and what group each customer falls into. 
 
 #### Methodology
 I did the following in Python: standardized the data, visualized the data, used the elbow method with the sum of squared errors to determine the optimal number of clusters, performed k-means cluster analysis, and then analyzed the clusters to determine their characteristics. 
 
 #### Findings
 
 I found that the range for age was very large and overlapped across clusters. I therefore concluded age to not be an important factor. 
 
Prior to clustering this data, I would have assumed a higher average income correlated to a higher average annual spend. However, Cluster 4's average income ranks in the middle, with an average not too much more than the first and second lowest income, and yet has the highest average annual spend. Additionally, they have a low average number of days since their last purchase. The customers in this cluster appear to have a lower income range, but shop frequently at the store, resulting in a higher annual spend. This cluster of customers could be receptive to a customer loyalty program that would encourage them to purchase and spend even more.

Another observation is that the highest average income spends the least annually. However, they also have the lowest average number of days since their last purchase. There is a potential opportunity to target these customers with discounts and other promotions to encourage them to purchase more frequently.
