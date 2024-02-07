# Inventory Analysis

Inventory analysis is a process to determine the optimal inventory level for a business by looking at 
the customer/production demand to minimize the amount of stock on hand to avoid overstocking and avoid 
inventory going out of stock and losing a customer to a competitor.

We use a dataset from a wonderful fictitious company named WarmeHands Inc. As with many retailers, 
they want to investigate possible improvements in inventory management and purchases provided by **Datacamp**


<p align="center">
  
  <img src="https://github.com/Ahmed-R-Hamdan/Power-BI---Inventory-Analysis/blob/main/image/Inventory%20Dashboard.JPG"/>

</P>

## Benefits of Inventory Analysis

- Reduction of storage expenses
- Reduction of purchase costs
- Reduction of unused goods
- Helps to increase profit

## Calculations used

- Revenues\
  Quantity of Units Sold * Selling Price
- Cost of Goods Sold (COGS)\
	Cost of producing such (Raw Material, Labor and production) excluding selling and transportation
- Profit\
	Gross Profit = Revenue - COGS


## Best Inventory Analysis Method

There are many ways to make inventory analysis you can read more from [here](https://adynamics.com.my/inventory-analysis/), but we will use ABC Analysis

### ABC Analysis 

ABC inventory analysis is a technique that determines the value of inventory items based on their importance
 to the business by classifying them into three groups (A, B, and C) in order to help inventory managers 
and business leaders to understand which products or services are the most critical to the financial success
 of the organization.

This technique is based on the Pareto rule of 80/20 as ABC analysis identifies the top 20% of inventory items
 that deliver about 80% of the value.

ABC Analysis in four steps

1 - Get revenue of your items\
2 - Calculate the percentage of Total Revenue\
3 - Sort percentage in a descending order and get cumulative increase\
4 - Classify items according to rule of how much they cover of total revenue
  - A Class covers 70 % of total revenue
  - B Class covers the following 20 %
  - C Class covers the remaining

![](https://github.com/Ahmed-R-Hamdan/Power-BI---Inventory-Analysis/blob/main/image/ABC%20analysis.JPG)

## Key Inventory Analysis Metrics (KPIs)

### 1- Inventory Turnover Ratio

The Inventory Turnover Ratio is a financial formula to measure how quickly your inventory is sold and replaced 
during a given period. The ratio considers the cost of inventory sold relative to its average inventory 
for a year in any set period of time.

The ratio is also useful when compared to the previous year’s ratio as well as the competitor’s ratio in order to
 analyze any trends, and business performance and it gives an idea of how efficiently your company is managing
 its inventory.

$$Inventory Turnover Ratio (ITR) = \frac{COGS } {Average Value Inventory}$$

### 2- Average Inventory 

Average Inventory is a calculation to estimate an amount or value of inventory a business has over a specific 
period of time. This is to balance large spikes in inventories during high seasons, 
large shipments received, or sudden buying surges. Usually, this is done at the beginning and end of 
the accounting period.

$$Average Value Inventory = \frac{(Beginning Value Inventory + Ending Value Inventory)}  {2}$$
