✔ This project demonstrates the use of PySpark for data manipulation and analysis. Below is a step-by-step guide on how to execute various operations using PySpark.

* Steps
Import Libraries

Import PySpark and Pandas libraries.
Define Data

Create a dataset with details including first name, middle name, last name, date of birth (dob), gender, and salary.
Define Schema

Define column names for the dataset.
Create DataFrame

Use spark.createDataFrame to create a DataFrame with the defined data and schema.
Display the DataFrame using df_pyspark.show().
Initialize Spark Session

Import SparkSession from PySpark and initialize it.
Load CSV File

Specify the file path of the CSV file.
Load the CSV file into a DataFrame using spark.read.format("csv").
Display the DataFrame using df1.show().
Print Schema

Display the schema of the DataFrame using df1.printSchema().
Data Type Casting

Change the data type of the 'salary' column to Integer using withColumn.
Add a Column

Add a new column 'bonus' to the DataFrame, calculated as 20% of the salary.
Filter Data

Filter rows where the name is 'vidhi'.
Filter rows where the name is 'vidhi' or 'piyush'.
Filter rows where the salary is between 15000 and 20000.
Filter rows where the salary is not less than or equal to 20000.
Sort Data

Sort the DataFrame by the 'salary' column in ascending and descending order.
Select Columns

Select specific columns ('name', 'salary', 'address') from the DataFrame.
Aggregate Functions

Calculate the sum, average, count, minimum, and maximum of salaries grouped by address.
Create Another DataFrame

Create a second DataFrame with employee details, including superior employee ID, year joined, department ID, and gender.
Display the schema and the DataFrame.
Department Data

Create a DataFrame for departments with department names and IDs.
Display the schema and the DataFrame.
Join Operations

Perform inner, left, right, and outer joins between the employee and department DataFrames.
Union Operation

Create additional DataFrames and perform a union operation to combine them.
These steps outline the process of working with data in PySpark, including loading data, transforming it, and performing various operations such as filtering, sorting, and aggregating.






