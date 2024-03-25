# PySpark Data Cleaning and Processing Essentials: With Real World Scenario:

This project aims to perform data cleaning and processing tasks on a dataset using PySpark. Below is a summary of frequently used functions when working with PySpark DataFrames. These functions are used to perform various data processing tasks such as data reading, description, handling missing values, manipulation, filtering, querying, adding new columns, and selecting/merging columns.

## Data Reading and Loading

- `take`: Takes a specified number of rows from the DataFrame.
- `show`: Displays the contents of the DataFrame in a specified way.
- `collect`: Collects all data from the DataFrame and returns it as a local list.

## Data Description

- `schema.names`: Returns the column names of the DataFrame.
- `printSchema()`: Prints the schema of the DataFrame.
- `columns`: Returns the names of the columns in the DataFrame.
- `count()`: Returns the total number of rows in the DataFrame.
- `describe().show()`: Shows statistical summary information for numerical columns.
- `summary().show()`: Shows summary statistics of the DataFrame.

## Handling Missing Data

- `isNotNull()`: Filters non-null values in a specific column.
- `isNull()`: Filters null values in a specific column.
- `fillna()`: Fills missing values with specified values.

## Filtering and Cleaning

- `drop()`: Deletes specific columns or rows.
- `dropDuplicates()`: Removes duplicate rows based on specific columns.
- `filter`: Filters rows that satisfy a specific condition.
- `where`: Filters rows that satisfy a specific condition.
- `when`: Returns a value when a specific condition is met.

## Data Manipulation

- `regexp_extract()`: Extracts text based on a given regular expression.
- `regexp_replace()`: Replaces text using regular expressions.
- `alias`: Used to rename a column.
- `select()`: Selects specific columns.
- `withColumn`: Adds a new column or modifies an existing one.
- `monotonically_increasing_id()`: Adds a unique monotonically increasing ID column to the DataFrame.

## Data Type Conversions

- `cast()`: Changes the data type of a column.
  
## Data Merging

- `union`: Merges two DataFrames.
- `join()`: Merges two DataFrames based on a specified column.

## PySpark and Pandas Comparison

- `read_with_pandas()`: Reads data using Pandas. This function reads the data as a Pandas DataFrame.
- `read_with_pyspark()`: Reads data using PySpark. This function reads the data as a PySpark DataFrame.
- `pyspark_vs_pandas_file_reading()`: This function compares the file reading times by calling the `read_with_pandas()` and `read_with_pyspark()` functions using each library. Then, it prints the results to the screen.

## License

This project is licensed under the MIT License. For more information, please see the [LICENSE](LICENSE) file.

## How to Run

1. Clone <a href="https://github.com/EmrullahCelk/PySpark.git">the project</a>
2. Install PySpark
3. Open the `pyspark_for_beginners.ipynb` file.
4. Execute the notebook cells sequentially to observe PySpark operations.

