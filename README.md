# Data Cleaning and Processing with PySpark

This project aims to perform data cleaning and processing tasks on a dataset using PySpark. Below is a summary of frequently used functions when working with PySpark DataFrames. These functions are used to perform various data processing tasks such as data reading, description, handling missing values, manipulation, filtering, querying, adding new columns, and selecting/merging columns.

## Data Reading and Loading

- `take`: Takes a specified number of rows from the DataFrame.
- `show`: Displays the contents of the DataFrame in a specified way.
- `collect`: Collects all data from the DataFrame and returns it as a local list.

## Data Description

- `schema.names`: Returns the column names of the DataFrame.
- `describe().show()`: Shows statistical summary information for numerical columns.
- `summary().show()`: Shows summary statistics of the DataFrame.

## Handling Missing Data

- `isNotNull()`: Filters non-null values in a specific column.
- `isNull()`: Filters null values in a specific column.

## Data Manipulation

- `regexp_extract`: Extracts text based on a given regular expression.

## Filtering and Selecting

- `filter`: Filters rows that satisfy a specific condition.
- `where`: Filters rows that satisfy a specific condition.
- `when`: Returns a value when a specific condition is met.
- `alias`: Used to rename a column.

## Querying and Statistics

- `count`: Returns the number of rows that satisfy a specific condition.

## Adding New Columns

- `withColumn`: Adds a new column or modifies an existing one.
- `monotonically_increasing_id()`: Adds a unique monotonically increasing ID column to the DataFrame.

## Selecting and Merging Columns

- `select()`: Selects specific columns.
- `union`: Merges two DataFrames.
- `dropDuplicates()`: Removes duplicate rows based on specific columns.

## PySpark and Pandas Comparison

- `read_with_pandas()`: Reads data using Pandas. This function reads the data as a Pandas DataFrame.
- `read_with_pyspark()`: Reads data using PySpark. This function reads the data as a PySpark DataFrame and can be used to measure time using the `timeit` module.

## License

This project is licensed under the MIT License. For more information, please see the [LICENSE](LICENSE) file.

## How to Run

1. Clone the repository using the following link: [https://github.com/EmrullahCelk/PySpark.git](https://github.com/EmrullahCelk/PySpark.git)
2. Install PySpark: [PySpark Installation Guide](https://spark.apache.org/docs/latest/api/python/getting_started/index.html)
3. Run Jupyter Notebook.
4. Open the `pyspark_for_beginners.ipynb` file.
5. Execute the notebook cells sequentially to observe PySpark operations.

