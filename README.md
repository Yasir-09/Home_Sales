# Home_Sales
This is challenge 22 for the UofT SCS Data Analytics Boot Camp.

**About the Challenge**

This project required to apply PySpark and SparkSQL dependencies to analyze home sales data. It reads data from an AWS S3 bucket, converts the data to a Spark DataFrame, creates temporary views of the data, caches the views, and performs various SQL queries on the cached data.

The script requires Spark and Java to be installed. It downloads and installs the latest version of Spark, and I downloaded spark-3.5.0 3.x, installs Java, and sets environment variables. It also imports the necessary packages, including pandas and findspark.

**Following task were performed to apply queries on the home sales data as required by the challenge:**

•	Read in the AWS S3 bucket into a DataFrame.

<br>•	Created a temporary view of the DataFrame.<br>

<br>•	Determined the average price for a four-bedroom house sold in each year rounded to two decimal places?<br> 
•	Determined the average price of a home for each year the home was built that have 3 bedrooms and 3 bathrooms rounded to two decimal places? 
•	Found the average price of a home for each year built that have 3 bedrooms, 3 bathrooms, with two floors, and are greater than or equal to 2,000 square feet rounded to two decimal places? 
•	Found what is the "view" rating for the average price of a home, rounded to two decimal places, where the homes are greater than or equal to $350,000?Although this is a small dataset, determine the run time for this query. 
•	Cached the temporary table home_sales. 
•	Checked if the table was cached.
•	Used the cached data, run the query that filters out the view ratings with average price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime. 
•	Partitioned by the "date_built" field on the formatted parquet home sales data. 
•	Read the parquet formatted data. 
•	Created a temporary table for the parquet data. 
•	Ran the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
•	Uncached the home_sales temporary table.
•	Verified that the home_sales temporary table is uncached using PySpark.
