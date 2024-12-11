# Home_Sales
# Home Sales Analysis using PySparkSQL

## Overview
This project uses PySparkSQL to analyze home sales data. You'll determine key metrics about the dataset, perform operations such as creating temporary views, caching and uncaching tables, and partitioning data. The goal is to enhance your understanding of PySpark's SQL functionality and data processing capabilities.

## Prerequisites
- Python 3.x
- PySpark installed
- A GitHub account and Git installed on your local machine
- Basic knowledge of SQL and Python

## Getting Started

### Repository Setup
1. **Create Repository**: Create a new repository named `Home_Sales` on GitHub.
2. **Clone Repository**: Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/Home_Sales.git
   Instructions
### 1. Data Loading
Import the necessary PySpark SQL functions.
Load the home_sales_revised.csv file into a Spark DataFrame.
### 2. Temporary Table Creation
Create a temporary table named home_sales.
### 3. Data Analysis Using SparkSQL
Answer the following questions using SparkSQL:

Average Price for Four-Bedroom Homes:

Calculate the average price of four-bedroom houses sold for each year.
Round results to two decimal places.
Average Price for Homes with 3 Bedrooms and 3 Bathrooms:

Calculate the average price for each year the home was built.
Round results to two decimal places.
Specific Home Price Analysis:

Find the average price of homes built in a specific year with:
Three bedrooms
Three bathrooms
Two floors
At least 2,000 square feet.
Round results to two decimal places.
Price by View Rating:

Determine the average price of homes per "view" rating where the average home price is ≥ $350,000.
Calculate and record the query's runtime.
### 4. Caching Operations
Cache the home_sales temporary table.
Verify that the table is cached.
### 5. Performance Comparison
Run the "Price by View Rating" query using cached data.
Compare the runtime with the uncached version.
### 6. Data Partitioning
Partition the data by date_built and save it in Parquet format.
Create a temporary table for the partitioned Parquet data.
Run the "Price by View Rating" query again and compare runtimes.
### 7. Uncaching Operations
Uncache the home_sales temporary table.
Verify that the table is uncached.
Submission

Download the completed Home_Sales.ipynb file.
Upload it to your Home_Sales GitHub repository.
Push all changes to GitHub
