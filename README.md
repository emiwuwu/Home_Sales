# Home Sales Data Analysis with SparkSQL

## Project Overview

In this project, I leveraged SparkSQL to conduct a comprehensive analysis of home sales data. The primary objectives included extracting crucial metrics, establishing temporary views, partitioning the dataset, caching and uncaching a temporary table, and confirming the caching status. These processes were instrumental in enabling me to effectively explore and analyze the dataset.

## Key Steps

1. Imported essential PySpark SQL functions.
2. Read the home sales data into a Spark DataFrame.
3. Created a temporary table named "home_sales."
4. Employed SparkSQL to address specific questions, including the computation of average property prices based on different property types and conditions.
5. Executed a query to filter the data according to specified criteria.
6. Cached the temporary table to enhance performance.
7. Verified the caching status of the temporary table.
8. Executed the same queries as in step 5 on the cached data, measuring the runtime.
9. Optimized data organization by partitioning it based on a relevant field.
10. Established a temporary table for the partitioned parquet data.
11. Executed the same queries as in step 5 on the partitioned data, calculating runtime.
12. Uncached the temporary table to release resources.
13. Confirmed the uncaching of the temporary table using PySpark.

Through the completion of these tasks, I gained valuable insights from the home sales dataset, enabling data-driven decision-making, and a better understanding of big data analysis.
