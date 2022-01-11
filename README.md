# Dynamic-Pricing

## Question Description
K-Fashion is a boutique store for women’s fashion apparel located in a big shopping mall at the Causeway Bay. The store is targeting young female white-collar who care less about brand but more about fashion and price. 

For the next season (10 weeks), K-Fashion has ordered 200 different stock keeping units1 (SKUs) from a foreign supplier. Due to the long production and order lead time, K-Fashion can place the order only once. Given the large store traffic at Causeway Bay, the store ordered 15 pieces for each SKU. 

Your job is to focus on the pricing of the three SKUs—A, B, and C—of a particular style. The sales of this style are independent of other styles. The goal is to maximize the total revenue, given the fixed amount of inventory over the next 10 weeks. Any unsold inventory after the tenth week will be discarded with zero salvage value. The constraint is that you must set the same price for all the three SKUs as they differ only in color or size. The price can be adjusted every Monday. You must pick a price from the set: {999, 899, 799, 699, 599, 499, 399, 299, 199, 99}. 

Customers arrive randomly. Historical data suggests that the traffic is smaller in the first two months or 8 weeks and larger in the last 2 weeks. For the first 8 weeks, the weekly totalnumber of visits to the store approximately follows normal distribution with a mean of 1000 and a standard deviation of 250; for the last 2 weeks, the weekly total visits also follows normal distribution with a mean of 2000 and a standard deviation of 500. The number of visits will be an integer. 

According to past experience, about one out of fifty (1/50) customers on average will show interests in the focal style (i.e., ask about the price and/or try it on). These customers will likean SKU with an equal probability (i.e., 1/3), but they will never consider buying two or more SKUs of the same style. Hence, the chance that a customer entering the store will consider SKU A as the first choice is (1/50)*(1/3). However, the demand can be substituted among different SKUs. For example, customers that suit size M may buy size L. Based on past experience, you believe that the table below describes the conditional probability of substitution given that a available. Demand will not be substituted twice. In other words, a customer who considers A as the first choice and B the second choice will never buy C.


Please collaborate with your teammates to find out a scientific way of setting the price of each week in order to maximize the total revenue. You can use Monte Carlo Tree Search or other methods.

Your strategy will be tested in class (the last session). On that day, you will make decisions on the fly, and your performance (total revenue) will be compared against other teams. The team that achieves the highest total revenue will receive an award. The score of each team will be determined according to a comparison against the highest possible total revenue. The team that does not show up or participate in the competition will receive a score of zero.

## Files Description
1. Simulation:

Generate simulated data according to the distribution provided by question.

2. Monte Carlo Tree Search:

Build Monte Carlo Tree Search algorithm, and use simulated data to build the tree.
