## Instacart Market Basket Analysis

Instacart, a grocery ordering and delivery app, aims to make it easy to fill your refrigerator and pantry with your personal favorites and staples when you need them. After selecting products through the Instacart app, personal shoppers review your order and do the in-store shopping and delivery for you.

### Objective
Use the anonymized data on customer orders over time provided by [Instacart](https://www.instacart.com) to predict which previously purchased products will be in a user’s next order. 

### Required libraries
- NumPy
- Pandas
- scikit-learn
- seaborn
- matlibplot
- lightGBM

### Data

- aisles.csv: Match aisle ID and aisle name
- departments.csv: Match department ID and department name
- order_products_prior.csv: Previous order contents for all customers
- order_products_train.csv: Order contents for training 
- order.csv: Tells which set(prior, train, test) an order belongs
- products.csv: Match product ID and product name and aisle ID, department ID

### Analysis

First we do EDA to examine data distribution and trend. Then we use naive approach to set up benchmark, which is to predict user will buy whatever he/she has purchased before. 

### Reference
[Kaggle competition](https://www.kaggle.com/c/instacart-market-basket-analysis)