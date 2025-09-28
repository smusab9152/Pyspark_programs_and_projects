# PySpark Programs and Projects
This repository is a collection of PySpark programs, examples, and mini-projects designed for learning and demonstrating the core functionalities of Apache Spark with Python. It covers fundamental concepts from RDDs to DataFrames and Spark SQL.

## About The Project
Apache Spark is a powerful open-source, distributed computing system used for big data processing and analytics. PySpark is the Python API for Spark, which allows you to harness the power of Spark using the simplicity of Python.
This repository serves as a practical guide, providing hands-on examples to help you understand and implement various PySpark operations.

## Programs & Projects Included
This collection demonstrates a range of PySpark functionalities. Below is a list of the key programs available in this repository.
- `Introduction to RDDs (Resilient Distributed Datasets)`: 
Description: Covers the fundamentals of RDDs, including creation, transformations (map, filter, flatMap), and actions (collect, count, reduce). This is the low-level API of Spark.
- `Working with the DataFrame API`:
Description: A comprehensive look into Spark DataFrames, the modern, structured data API. This includes selecting, filtering, grouping, and aggregating data, as well as handling columns (withColumn, drop).
- `Spark SQL and Queries`:
Description: Demonstrates how to run SQL queries directly on DataFrames. This practical shows how to create temporary views and leverage the power of SQL for data manipulation and analysis within a Spark environment.
- `Data Ingestion and Egress (I/O)`:
Description: Examples of reading from and writing to various data sources and formats, such as CSV, JSON, and Parquet, which is a columnar storage format optimized for Spark.
- `Handling Missing Data`:
Description: A practical guide to common data cleaning techniques in PySpark, including how to identify, count, and handle null or missing values in a large-scale dataset.

## 🛠️ Getting Started
To run these PySpark programs on your local machine, you'll need to have Apache Spark and Python installed and configured.

### Prerequisites
- Python (3.6+)
- Apache Spark: Download from the official website.

### Installation & Setup

Clone the repository:
```bash
git clone https://github.com/smusab9152/Pyspark_programs_and_projects.git]
```
Navigate to the project directory:
```bash
cd Pyspark_programs_and_projects
```
Install PySpark library:
It is recommended to use a virtual environment.
```bash
pip install pyspark
```

Set Environment Variables (Crucial Step):
You must tell your system where to find Spark. Set SPARK_HOME and add it to your PATH.

- On macOS/Linux:
```bash
export SPARK_HOME=/path/to/your/spark-directory
export PATH=$SPARK_HOME/bin:$PATH
```
- On Windows:
Set the variables through the "Environment Variables" system settings.

- Run a Script or Launch a Notebook:
You can now run a python script or start a Jupyter Notebook and import pyspark.

## Tools & Technologies Used
- Apache Spark
- Python
- PySpark API
- Jupyter Notebook (for interactive notebooks)
