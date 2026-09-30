# Apple Financial Analysis

## Project Overview

This project analyzes Apple's financial performance from 2009 to 2024 using Python, Pandas, Matplotlib, and SQL.

The goal is to examine revenue growth, profitability, financial margins, earnings per share, stock price dynamics, and debt levels.

## Dataset

The dataset contains 16 years of Apple's financial data and includes:

* Revenue
* EBITDA
* Gross Profit
* Operating Income
* Net Income
* EPS
* Year-End Stock Price
* Total Assets
* Cash
* Long-Term Debt
* Total Liabilities
* Gross Margin
* P/E Ratio
* Number of Employees

## Data Quality

The dataset contains:

* 16 observations
* 16 variables
* No missing values
* No duplicate rows
* Numeric financial variables are stored as numeric data types

## Analysis

The project includes:

* Data loading and inspection
* Data quality checks
* Revenue growth analysis
* Net income growth analysis
* Net profit margin calculation
* EBITDA margin calculation
* Operating margin calculation
* Debt-to-assets analysis
* EPS analysis
* Stock price analysis
* Descriptive statistics
* SQL analysis
* Data visualization

## Key Findings

The analysis covers the period from **2009 to 2024**.

### Revenue

Apple's revenue increased from **$42,905 million in 2009** to a maximum of **$394,328 million in 2022**.

The highest year-over-year revenue growth in the dataset occurred in **2011**, when revenue increased by approximately **65.96%**.

Revenue also experienced declines in several years, showing that growth was not consistent throughout the entire period.

### Net Income

Net income increased from **$8,235 million in 2009** to a maximum of **$99,803 million in 2022**.

The highest year-over-year net income growth occurred in **2011**, at approximately **84.99%**.

The comparison between revenue and net income growth shows that changes in profitability were not always proportional to changes in revenue.

### Profitability

The highest calculated net profit margin in the dataset occurred in **2012**, reaching approximately **26.67%**.

Profitability was analyzed using several indicators:

* Net Profit Margin
* EBITDA Margin
* Operating Margin

These metrics provide different perspectives on Apple's operating and overall profitability.

### Financial Structure

The project also analyzes long-term debt relative to total assets using a Debt-to-Assets ratio.

This provides an additional view of the company's financial structure alongside its revenue and profitability trends.

## SQL Analysis

SQL queries were used to:

* Inspect the financial dataset
* Identify years with the highest revenue
* Identify years with the highest net income
* Calculate net profit margins
* Rank years by profitability

SQLite was used to perform the SQL analysis directly in the Python environment.

## Visualizations

The project includes visualizations of:

* Revenue and Net Income dynamics
* Net Profit Margin
* EPS dynamics
* EPS and year-end stock price
* Other financial indicators

## Technologies

* Python
* Pandas
* Matplotlib
* SQLite
* SQL
* Google Colab
* GitHub

## Project Structure

```text
Apple-Financial-Analysis/
│
├── financial_analysis.ipynb
├── Apple_Financial_Analysis.csv
├── analysis.sql
└── README.md
```

## Key Questions

The analysis focuses on the following questions:

1. How did Apple's revenue change from 2009 to 2024?
2. How did net income change over the same period?
3. Which years had the highest revenue and net income growth?
4. How did Apple's profitability change over time?
5. How did EPS and year-end stock price change?
6. How did long-term debt compare with total assets?
7. Which years had the highest net profit margins?

## Conclusion

This project demonstrates an end-to-end financial data analysis workflow using Python and SQL. It combines data quality assessment, financial calculations, statistical analysis, SQL queries, and data visualization to examine Apple's historical financial performance.
