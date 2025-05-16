# Market-Basket-Analysis-Project
This project uses the UCI Online Retail Dataset to explore customer purchasing behavior using the Apriori algorithm. The goal is to find strong association rules between commonly purchased items and visualize them with lift and confidence metrics.

## Dataset

- **Source**: UCI Machine Learning Repository
- **Description**: Contains transactional data for an online UK-based retailer between 01/12/2010 and 09/12/2011.
- **Fields**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Objective

- Apply market basket analysis using the Apriori algorithm
- Generate high-lift association rules with strong support and confidence
- Visualize the strongest rules using network graphs and bar plots

## Techniques Used

- Data Cleaning (removing canceled and null transactions)
- Transaction encoding and basket creation
- Apriori algorithm via `mlxtend`
- Association rule generation and filtering
- Visualization using `networkx`, `matplotlib`, and `seaborn`

## Example Output

- Rules like:  
  `"HERB MARKER MINT, HERB MARKER ROSEMARY" → "HERB MARKER PARSLEY, HERB MARKER THYME"`  
  had a **lift of 95.24** and **confidence of 1.0**, suggesting strong item affinity.

