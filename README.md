# Data Transformation and Integration with PySpark

This project demonstrates data transformation and integration using PySpark. I worked with two datasets and applied various transformations, including adding columns, renaming columns, dropping unnecessary columns, and joining DataFrames. The final results were written to both a Hive warehouse and the HDFS file system.

**Prerequisites**: This project involves using wget, Python, and Spark (PySpark). Ensure that these tools and libraries are installed in the lab environment.

## Tasks
- Creating a SparkContext object
- Load datasets into PySpark DataFrames
- Display the schema of both dataframes
  ![Result Image](Results/printschema.png)
- Add a new column to each dataframe
- Rename columns in both dataframes
- Drop unnecessary columns
- Join dataframes based on a common column
- Filter data based on a condition
- Aggregate data by customer
- Write the result to a Hive table
- Calculate the average transaction value per quarter
- Calculate the total transaction value per year
- Write the result to HDFS

**Dislaimer**: This project was completed as part of my final exam for the IBM course BD0225EN: Big Data, Hadoop, and Spark Basics. My certificate can be found [here](https://courses.edx.org/certificates/9d3b18f1586a4eff8e49a56102521231). This project is the property of IBM through EdX, and all rights are reserved.
