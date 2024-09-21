# SparkSQL Home Sales Analysis 

## Overview
This project analyzes home sales data using Spark & SparkSQL for loading, caching and partitioning data to derive key metrics,  optimize and compare process performance.

## Libraries/Language
- Python 3.12
- PySpark
- Spark SQL
- Jupyter Notebook

## Project Summary
The Jupyter notebook follows these steps:

1. **Data Loading:** Load home sales data into Spark DataFrame.
2. **Creating Temporary Tables:** Create temporary table for SparkSQL queries.
3. **Querying Data:** Perform queries to calculate key metrics like average home price.
4. **Caching Data:** Cache the table and store it in memeory to optimize query performance.
5. **Performance Comparison:** Compare runtimes of cached and uncached queries.
6. **Partitioning Data:** Partition data to further optimize performance.
7. **Querying Partitioned Data:** Run queries on partitioned data for comparison.
8. **Uncaching Table:** Free up memory used to store cached tables by uncaching tables.

## Results
- **Caching:** Query runtimes were faster with cached data compared to the uncached version, demonstrating the performance benefits of caching.
- **Partitioning:** Partitioning by the `date_built` field further optimized query runtimes, showing improved efficiency for querying large datasets.
- **Average Prices:** Insights into average home prices based on different criteria, including year, bedrooms, bathrooms, and view ratings, were successfully calculated and visualized.

## Works Cited
- ChatGPT for assistance with PySpark functions and query optimization.

## License
- GNU GENERAL PUBLIC LICENSE.
