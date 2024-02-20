# E-Commerce Data Analysis with Elasticsearch

## Project Description 

This project entails comprehensive analysis of e-commerce data using SQLite and Elasticsearch. It begins with importing the Kaggle E-commerce dataset into SQLite, followed by SQL queries to explore key attributes, patterns, and conduct basic data cleaning. The focus then shifts to Elasticsearch for indexing and querying the dataset, facilitating further exploration and analysis.

### SQL Exploration

In the initial phase, SQL queries are employed to delve into the dataset:

- Identify total unique products and customers.
- Calculate total revenue for each product (top 5).
- Determine most profitable countries by total sales (top 5).
- Find top-selling products by total sales and quantity for each country (top 5).

### Setting up Elasticsearch

The process of setting up Elasticsearch involves the following steps:

1. **Download Elasticsearch:** The Elasticsearch package is downloaded and extracted from the official source.
2. **Start Elasticsearch:** The Elasticsearch server is started in the background.
3. **Verify Elasticsearch:** Verification of the Elasticsearch server status is performed to ensure successful setup.

### Setting up Elasticsearch Index

After preprocessing the data by dropping rows with missing values, an Elasticsearch index is created. This index serves as a database for storing, searching, and analyzing the dataset.

### Verifying the Index

The created Elasticsearch index is verified to ensure proper configuration and data integrity. Verification includes checking the columns and the number of rows in the index.

### Running Elasticsearch Queries

After cleaning the e-commerce data, Elasticsearch queries are executed to gain insights that will inform the expansion strategy, focusing on Germany:

1. **Find all transactions for Germany:** Understand the contribution of different countries to sales, focusing on Germany.
2. **Find all unique products in Germany:** Assess the breadth of the product portfolio in Germany.
3. **Find the top 5 most purchased products in Germany:** Identify the best-selling products in Germany to guide marketing efforts and product focus.

Executing these tasks provides data-driven insights crucial for strategic decisions about business expansion. Additionally, tasks to handle date type data and test product search feature using partial keyword matching are included to ensure robustness and reliability of the analysis.
