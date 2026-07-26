# Apache Spark DataFrame Assignment (Week 6)

## Overview

This repository contains solutions for the Apache Spark Week 6 Assignment using PySpark. The assignment demonstrates fundamental DataFrame operations such as reading CSV files, filtering records, selecting columns, renaming columns, type casting, creating new columns, reading and writing Parquet files, and applying conditional queries.

The project is implemented using **PySpark** and focuses on understanding Spark DataFrame transformations and actions.

---

## Objectives

- Read CSV files using Spark DataFrames.
- Perform filtering using multiple conditions.
- Select required columns.
- Rename existing columns.
- Cast data types.
- Create calculated columns.
- Read Parquet files.
- Export processed data as CSV.
- Apply logical operators (AND / OR).
- Understand Spark DataFrame transformations.

---

## Technologies Used

- Python 3.x
- Apache Spark 3.5.x
- PySpark
- Java JDK
- VS Code

---

## Project Structure

```
Spark_Assignment/
│
├── spark_assignment.py
├── dataset.csv
├── README.md
└── output/
```

---

## Assignment Tasks

### Task 1
Create a Spark Session.

### Task 2
Read a CSV file with:
- Header enabled
- Schema inference enabled

### Task 3
Display the DataFrame.

### Task 4
Filter products belonging to the **Electronics** category.

### Task 5
Rename a column and cast the **price** column to DoubleType.

### Task 6
Filter completed orders where the amount is greater than 1000.

### Task 7
Create a new column named **final_price** by adding 18% tax.

### Task 8
Read a Parquet file, remove rows with null user IDs, and save the cleaned data as CSV.

### Task 9
Filter records where:
- Region = North
- OR Priority = High

### Task 10
Stop the Spark Session.

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/Spark_Assignment.git
```

### Move into the project directory

```bash
cd Spark_Assignment
```

### Install PySpark

```bash
pip install pyspark
```

### Execute the program

```bash
python spark_assignment.py
```

---

## Learning Outcomes

After completing this assignment, you will understand:

- SparkSession creation
- DataFrame operations
- Reading CSV and Parquet files
- Data filtering
- Column selection
- Column renaming
- Data type conversion
- Creating calculated columns
- Writing output files
- Spark transformations and actions

---

## Sample Operations Used

- `read.csv()`
- `filter()`
- `select()`
- `withColumn()`
- `withColumnRenamed()`
- `cast()`
- `read.parquet()`
- `write.csv()`
- `show()`

---

## Requirements

- Python 3.x
- Apache Spark
- Java JDK
- PySpark

---

## Author

Nishita Raj

---

## License

This project is created for educational purposes as part of an Apache Spark coursework assignment.
