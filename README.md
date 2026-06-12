# Market-Basket-Analysis

This project applies **Market Basket Analysis** to identify product purchasing patterns and associations within transaction data. The goal is to discover which items are frequently purchased together and generate useful association rules that can support business decisions such as product placement, promotions, recommendation systems, and inventory planning.

## Project Overview

Market Basket Analysis is a data mining technique commonly used in retail and e-commerce to understand customer purchasing behavior. In this project, I use transaction-level data to find frequent itemsets and association rules using metrics such as **support**, **confidence**, and **lift**.

The analysis is completed in a Jupyter Notebook:

* `Market_Basket_Analysis.ipynb`

## Objectives

The main objectives of this project are to:

* Clean and prepare transactional data for analysis
* Transform the data into a format suitable for market basket analysis
* Identify frequently purchased item combinations
* Generate association rules using the Apriori algorithm
* Interpret the strongest product relationships using support, confidence, and lift
* Provide business insights based on customer purchasing patterns

## Methods Used

This project includes the following steps:

1. **Data Loading**
   Importing the dataset into Python for analysis.

2. **Data Cleaning and Preparation**
   Handling missing values, removing unnecessary fields, and preparing transactions.

3. **Transaction Encoding**
   Converting transaction data into a basket format where each row represents a transaction and each column represents an item.

4. **Frequent Itemset Mining**
   Applying the Apriori algorithm to find item combinations that occur frequently.

5. **Association Rule Mining**
   Generating rules that show relationships between items.

6. **Rule Evaluation**
   Analyzing rules using:

   * **Support**: How often an itemset appears in all transactions
   * **Confidence**: How often the rule is correct
   * **Lift**: How much more likely items are purchased together compared to random chance

## Technologies Used

* Python
* Jupyter Notebook
* pandas
* mlxtend
* matplotlib / seaborn
* NumPy

## Key Concepts

### Support

Support measures how frequently an itemset appears in the dataset.

### Confidence

Confidence measures the likelihood that a customer who buys one item will also buy another item.

### Lift

Lift measures the strength of an association rule. A lift value greater than 1 suggests that the items are more likely to be purchased together than expected by chance.

## Example Use Cases

Market Basket Analysis can help businesses answer questions such as:

* Which products are commonly purchased together?
* What items should be placed near each other in a store?
* What product bundles could be promoted?
* What recommendations can be shown to customers?
* Which items could increase cross-selling opportunities?

## Repository Structure

```text
Market-Basket-Analysis/
│
├── Market_Basket_Analysis.ipynb   # Main Jupyter Notebook
├── README.md                      # Project documentation
└── LICENSE                        # License information
```

## How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/betulmesci/Market-Basket-Analysis.git
```

2. Navigate to the project folder:

```bash
cd Market-Basket-Analysis
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook Market_Basket_Analysis.ipynb
```

4. Run the notebook cells from top to bottom.

## Results

The notebook identifies frequent itemsets and association rules that reveal meaningful relationships between products. These insights can be used to better understand customer purchasing behavior and support retail decision-making.

## Future Improvements

Possible future improvements include:

* Adding more visualizations for frequent itemsets and association rules
* Comparing different support and confidence thresholds
* Creating an interactive dashboard
* Testing the analysis on larger or more recent retail datasets
* Building a simple recommendation system based on association rules

## Author

**Betul Mescioglu**

Data Science | Python | Excel | Analytics | Machine Learning

## License

This project is licensed under the terms included in the `LICENSE` file.
