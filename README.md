# PySpark

A structured learning repository covering Apache Spark with PySpark, including data reading, schema definition, DataFrame transformations, data writing, and introductory Spark SQL.

## Topics Covered

### 1. Data Reading
- Reading CSV and JSON files
- Schema inference
- Working with files stored in Databricks Volumes

### 2. Schema Definition
- Defining explicit schemas
- `StructType` and `StructField`
- Data types
- Structured and nested schemas

### 3. Data Transformation
- DataFrame selection and filtering
- Column creation and modification
- Conditional transformations using `when()` and `otherwise()`
- String functions
- Date and time functions
- NULL handling
- Removing duplicates
- Sorting
- Aggregations
- Joins
- Union and `unionByName()`
- Window functions
- User Defined Functions (UDFs)

### 4. Data Writing
- Writing DataFrames to CSV
- JSON
- Parquet
- Delta
- Append and overwrite modes
- Writing managed tables

### 5. Spark SQL
- Creating temporary views from DataFrames
- Running basic SQL queries
- Converting between DataFrame operations and Spark SQL

## Repository Structure

```text
PySpark/
│
├── 01_Data_Reading.ipynb
├── 02_Schema_Definition.ipynb
├── 03_Data_Transformation.ipynb
├── 04_Data_Writing.ipynb
└── 05_Spark_SQL.ipynb