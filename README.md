# TASK-2-E-Commerce-Exploratory-Data-Analysis
Exploratory Data Analysis of an e-commerce sales dataset using Microsoft Excel to analyze sales performance, customer activity, trends, distributions, and outliers.

This project focuses on performing Exploratory Data Analysis (EDA) on an e-commerce sales dataset using Microsoft Excel.

The objective was to examine the dataset, calculate descriptive statistics, identify patterns and trends, detect potential outliers, and generate meaningful observations that can support data-driven business decisions.

The main objectives of this project were to:

- Analyze the structure and characteristics of the dataset.
- Calculate basic descriptive statistics.
- Understand sales and customer activity.
- Analyze order status and payment methods.
- Examine product quantity and pricing patterns.
- Identify potential outliers using the Interquartile Range (IQR) method.
- Identify meaningful patterns and observations.
- Develop analytical thinking and data interpretation skills.

 Key Analysis Performed

 1. Sales Summary

The analysis produced the following sales metrics:

- Total Revenue: $1,264,762
- Average Sales: $1,053.97
- Maximum Sales: $3,456.40
- Minimum Sales: $11.39

 2. Data Summary

The dataset contained:

- Total Orders: 1,200
- Total Customers: 1,189
- Total Products: 7

 3. Quantity Analysis

The quantity analysis showed:

- Total Quantity Sold: 3,535
- Average Quantity per Order: 3
- Maximum Quantity: 5
- Minimum Quantity: 1

 4. Order Status Analysis

The distribution of orders by status was:

| Order Status | Number of Orders |
|--------------|-----------------:|
| Delivered | 231 |
| Shipped | 235 |
| Cancelled | 250 |
| Returned | 247 |
| Pending | 237 |

The results show that cancelled and returned orders represent a significant portion of the total orders and may require further investigation.

 5. Payment Method Analysis

The payment methods were analyzed based on the number of orders:

| Payment Method | Number of Orders |
|----------------|-----------------:|
| Credit Card | 234 |
| Debit Card | 232 |
| Cash | 246 |
| Online | 258 |
| Gift Card | 230 |

Online payment was the most frequently used payment method, while Gift Card had the lowest number of orders.

 6. Pricing Analysis

The pricing analysis showed:

- Average Unit Price: $356.41
- Highest Unit Price: $699.93
- Lowest Unit Price: $11.39
- Average Order Value: $1,053.97

These figures provide an overview of the price range and typical value of transactions within the dataset.

 Outlier Analysis:

The Interquartile Range (IQR) method was used to identify potential outliers in key numerical variables.

 Total Price

- Q1: $410.52
- Q3: $1,578.48
- IQR: $1,167.96
- Lower Bound: -$1,341.41
- Upper Bound: $3,330.41
- Maximum Value: $3,456.40

The maximum Total Price of $3,456.40 is above the calculated upper bound of $3,330.41, indicating a potential high-value outlier.

 Quantity

- Q1: 2
- Q3: 4
- IQR: 2
- Lower Bound: -1
- Upper Bound: 7
- Maximum Value: 5
- Minimum Value: 1

No potential outliers were identified in the Quantity column because the observed values fall within the calculated bounds.

 Unit Price

- Q1: $186.06
- Q3: $521.57
- IQR: $335.51
- Lower Bound: -$317.17
- Upper Bound: $1,024.83
- Maximum Value: $699.93
- Minimum Value: $11.39

No potential outliers were identified in the UnitPrice column because the observed values fall within the calculated bounds.

 Key Observations

The analysis generated the following observations:

1. The dataset contains 1,200 orders from 1,189 customers across 7 products.
2. Total revenue generated was $1,264,762, with an average sales value of $1,053.97 per order.
3. The average quantity purchased per order was 3 units, with quantities ranging from 1 to 5.
4. Online payment was the most frequently used payment method, accounting for 258 orders.
5. Gift Card was the least frequently used payment method, with 230 orders.
6. Cancelled orders accounted for 250 transactions, while returned orders accounted for 247 transactions.
7. A potential high-value outlier was identified in TotalPrice, where the maximum value of $3,456.40 exceeded the upper IQR boundary of $3,330.41.
8. No significant outliers were identified in the Quantity or UnitPrice columns based on the IQR method.
9. The analysis provides useful information about sales performance, customer activity, order behavior, payment preferences, and pricing patterns.

 Analytical Thinking

Analytical thinking was applied by comparing descriptive statistics, examining distributions, evaluating order and payment patterns, and investigating unusual values.

Rather than only calculating numerical measures, the analysis focused on interpreting what the results mean for the business. The identification of a potential high-value sales outlier also demonstrates the importance of investigating unusual transactions before making business conclusions.

 Tools Used

- Microsoft Excel
- Excel Formulas
- Descriptive Statistics
- PivotTables
- Conditional Formatting
- IQR Outlier Analysis
- Data Visualization

 Key Skills Demonstrated

- Data Analysis
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Analytical Thinking
- Outlier Detection
- Trend Analysis
- Data Interpretation
- Microsoft Excel
- Business Insight Generation

 Project Outcome

The Exploratory Data Analysis provided a clear understanding of the dataset's sales performance, customer activity, order distribution, payment preferences, pricing patterns, and potential outliers.

The findings from this project provide a foundation for creating an interactive sales dashboard and generating data-driven business recommendations.

This project demonstrates the use of Microsoft Excel to transform a cleaned e-commerce dataset into meaningful analytical insights. Through descriptive statistics, trend analysis, order and payment analysis, and outlier detection, the project demonstrates the ability to analyze data and communicate findings that can support business decision-making.
