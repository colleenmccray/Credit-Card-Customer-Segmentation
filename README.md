# AllLife Bank Customer Segmentation Project

## Context

AllLife Bank has identified the need to improve penetration in the credit card customer base. The Marketing team aims to run personalized campaigns for targeting new customers and upselling to existing ones. Simultaneously, the Operations team plans to upgrade the service delivery model to enhance customer support services. Both teams seek assistance from the Data Science team to identify customer segments based on spending patterns and interactions, providing actionable insights and recommendations.

## Objective

The primary objective is to identify distinct customer segments using clustering algorithms, considering financial attributes and interaction history. The goal is to provide strategic recommendations for personalized marketing and improved service delivery.

## Data Description

The dataset includes various customers' financial attributes such as credit limit, total number of credit cards, and interaction channels (bank visits, online logins, and calls). Key attributes in the dataset include:

* Sl_No: Primary key of records
* Customer Key: Customer identification number
* Average Credit Limit: Average credit limit for all credit cards
* Total credit cards: Total number of credit cards
* Total visits bank: Yearly total bank visits
* Total visits online: Yearly total online logins
* Total calls made: Yearly total calls to the bank or customer service

## Actionable Insights and Recommendations

### K-Means Cluster Profiling

**Cluster 0**

* 386 customers
* Average credit limit: $35k
* Credit cards: 4-6
* Prefer bank visits over calls or online services

**Cluster 1**

* 224 customers
* Lowest credit limit and credit cards
* Frequent calls to the bank

**Cluster 2**

* 50 customers
* Highest average credit limit
* Credit cards: 8-10
* Prefer online visits over calls or bank visits

### Hierarchical Cluster Profiling

**Cluster 0**

* 196 customers
* Average credit limit: $35k
* Credit cards: 6
* Prefer bank visits over calls or online services

**Cluster 1**

* 191 customers
* Average credit limit: $25k
* Credit cards: 5
* Most frequent bank visitors

**Cluster 2**

* 50 customers
* Highest credit limit: ~$145k
* Credit cards: 9
* Most frequent online visitors

**Cluster 3**

* 131 customers
* Lowest credit limit
* Average calls: 6 to the bank

**Cluster 4**

* 92 customers
* Second-lowest credit limit
* Frequent calls to the bank

## Recommendations

**1. Segmentation for Personalized Campaigns:**
* Utilize K-Means clusters for personalized campaigns, particularly focusing on clusters 3 and 4 from hierarchical clustering due to similar output trends.
* Improve segmentation using K-Means for a better understanding of customer base.
  
**2.Segment-Specific Strategies:**
* High credit card count + high visits: Investigate reasons for frequent bank visits, offer promotions for additional product purchases through personal interactions at bank locations.
* Low credit limit + high call volume: Address poor customer service concerns, enhance customer support, and build loyalty among customers with minimal product loyalty.

**3.Maintaining Loyalty for High Credit Limit + High Users + High Online Visits:**
* Incentivize loyal customers with campaigns offering point bonuses, gifts, thank-you letters, etc., to maintain customer loyalty.
