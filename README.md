# Day 13 – Inferential Statistics

## Project Overview

This project focuses on **Inferential Statistics using Python**. The analysis is performed using customer and order datasets to understand sampling, hypothesis testing, and statistical significance.

## Objectives

* Understand Population and Sample
* Perform Random Sampling
* Calculate Sample Mean
* Compare Sample Mean with Population Mean
* Understand Sampling Bias
* Perform Hypothesis Testing
* Understand Null and Alternative Hypothesis
* Calculate P-Value
* Perform Independent T-Test
* Interpret Statistical Significance

## Technologies Used

* Python
* Pandas
* SciPy
* CSV

## Files

```text
Day 13/
│
├── day13_inferential_stats.py
├── Capstone Customers.csv
└── Capstone Orders.csv
```

## Dataset

### Customers Dataset

Contains customer-related information such as:

* Customer ID
* Customer Name
* Region
* Segment

### Orders Dataset

Contains sales and order information such as:

* Order ID
* Customer ID
* Order Date
* Category
* Sales
* Quantity
* Discount
* Profit

## Analysis Performed

### 1. Sampling

Random samples were selected from the Orders dataset and sample statistics were calculated.

### 2. Group Comparison

Customer and order datasets were merged using `CustomerID`.

Profit was compared between different regions.

### 3. Hypothesis Testing

An independent **T-Test** was performed to determine whether there was a statistically significant difference in average Profit between the selected regions.

### 4. P-Value

The p-value was compared with the significance level:

```text
Significance Level = 0.05
```

Decision rule:

```text
p-value < 0.05  → Reject Null Hypothesis
p-value >= 0.05 → Do Not Reject Null Hypothesis
```

## Key Concepts

* Population
* Sample
* Random Sampling
* Sampling Bias
* Mean
* Hypothesis Testing
* Null Hypothesis
* Alternative Hypothesis
* P-Value
* Significance Level
* Independent T-Test
* Statistical Significance

## Key Insight

The analysis demonstrates how sample data can be used to make conclusions about a larger population. The T-Test and P-Value help determine whether the difference between two groups is statistically significant.

## How to Run

### Install Required Libraries

```bash
pip install pandas scipy
```

### Run the Python File

```bash
python day13_inferential_stats.py
```

Make sure the Python file and both CSV files are in the same folder.

## Project Status

**Day 13 – Inferential Statistics completed successfully.**

## Author
Manjunath Kumbar
