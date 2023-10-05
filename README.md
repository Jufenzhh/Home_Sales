# Home_Sales

The code starts by setting up the spark environment, installing necessary dependencies and creating a SparkSession for PySpark. 

The code reads data from an external source in the Pyspark Dataframe from a CSV file with S3 Bucket. 

Using the  CSV file data, temporary view tables are created using Pyspark Dataframes, which allows the code to run SQL queries. 

Using SQL queries, the code runs tasks such as calculating the averages, filtering data and grouping. 

The code then caches and uncaches the temporary tables in Spark to compare query performance; caching improves query performance. Cached data is 0.3 seconds faster than uncached. 

Finally, the code demonstrates reading and working with Parquet formatted data to read, create temporary tables, and run queries on Parquet Data. In comparison to cached and uncached data, Parquet data runs even faster. 
