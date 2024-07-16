# Glacier-Mass-Balance-Pyspark-Project
Glacier Pyspark Project
Introduction
Welcome to the analysis of glacier data using PySpark. This project leverages the power of PySpark to perform comprehensive data analysis on glacier data, which is stored in a CSV file. The objective of this project is to explore and analyze the temporal changes in glacier data by focusing on specific records from the 19th and 20th centuries.

PySpark, the Python API for Apache Spark, is a powerful tool for handling big data. It provides an efficient way to process large datasets and perform complex computations. In this project, we utilize PySpark’s DataFrame and SQL functionalities to read, process, and analyze glacier data effectively.

Key Objectives

1. Data Ingestion and Inspection:

Read the glacier data from a CSV file using PySpark.
Display the data to understand its structure and content.
Count the total number of records and print the schema to verify data types.

2. Creating Temporary SQL Views:

Create a temporary SQL view from the DataFrame to enable SQL querying.
Extract all records from the view to ensure the data has been loaded correctly.

3. Temporal Analysis:

Identify and extract the earliest and latest records from the 20th century (1900s) and the 21st century (2000s).
Combine these records to create a concise dataset that highlights significant temporal changes.

4. Combining Results:

Merge the extracted records from both centuries to form a comprehensive view of the glacier data across different time periods.

Significance

This analysis is significant for understanding the changes in glacier data over time, which can provide insights into climate change and its impact on glaciers. By using PySpark, we can efficiently process and analyze large datasets, making it an ideal tool for big data analysis.

Through this project, we demonstrate the practical application of PySpark in environmental data analysis, showcasing its capabilities in handling, processing, and deriving insights from large-scale datasets.
