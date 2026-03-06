#  Market Basket Analysis on Grocery Store Dataset

##  Project Overview
This project demonstrates Market Basket Analysis (MBA) on a small grocery store dataset.  
Market Basket Analysis is a data mining technique used to discover associations between items purchased together by customers.

The goal of this project is to analyze customer transactions and identify frequently bought item combinations.

---

##  Dataset Information

Dataset Name: GroceryStoreDataSet.csv  

The dataset contains 19 transactions from a grocery store.  
Each row represents the items purchased together in a single transaction.

Example Transactions:

Transaction 1  
Bread, Milk, Biscuit, Cornflakes  

Transaction 2  
Bread, Tea, Bournvita  

Transaction 3  
Jam, Maggi, Bread, Milk  

---

##  Objective

The main objectives of this project are:

- Understand customer purchasing behavior
- Identify products frequently bought together
- Generate association rules
- Help retailers improve product placement and promotions

---

##  Technique Used

This project uses Market Basket Analysis with the Apriori Algorithm.

Key concepts used in MBA:

- **Support** – How frequently an item appears in the dataset  
- **Confidence** – Probability that item B is bought when item A is bought  
- **Lift** – Strength of association between two items

---

## Tools & Technologies

- Python
- Pandas
- Mlxtend
- Jupyter Notebook

---

##  Example Insights

Some possible association rules discovered from the dataset:

- Bread → Milk  
- Tea → Biscuit  
- Maggi → Bread  

These insights help retailers to:
- Place related products closer
- Create combo offers
- Increase cross-selling

---

##  Applications

Market Basket Analysis is widely used in:

- Retail stores
- Supermarkets
- E-commerce platforms
- Recommendation systems

Example:  
“Customers who bought Milk item also Bread”
