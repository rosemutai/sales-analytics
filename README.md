# Sales Analytics Without Pandas

The goal of this project was to answer a retailer's revenue questions using only the csv module, dictionaries and own functions — then let pandas check the homework.


## Python Skills
- CSV
- Dictionaries
- Tuples
- Comprehensions
- Functions
- Exception handling
- Algorithms
- Pandas

### Prerequisites

An understanding of Python 

### Install

In order to run this project you need to have the following:
- A code editor (VSCode)

### Setup

To get a local copy up and running follow these simple example steps:
- Open git bash on a local computer
- clone the repo with: 
  
```
git clone  <https://github.com/rosemutai/sales-analytics.git>
```

- run ```cd sales-analytics-main``` to enter the project folder
- run ```pip install -r requirements.txt``` to install all dependencies
- Click `Run All` to run the `sales_analysis.ipynb` file

## Analysis

### Tie-Breaking
Implemented `top_n` function to rank products by revenue in descending order. It returns a list of (product, revenue) tuples containing up to n products. When two products have the same total revenue, they are sorted alphabetically by product name in ascending order. 