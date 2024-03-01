# Enhanced Customer Satisfaction through ATM Analytics
Big Data Tech & App Course Project


This project focuses on analyzing Spar Nord Bank's ATM transaction data to gain insights into customer behavior, transaction patterns, and potential cost-saving opportunities. By leveraging data engineering, data analytics, and data visualization techniques, we aim to uncover valuable insights that can inform decision-making processes and optimize the bank's ATM network.

# Approach
Data Engineering Process
The data is extracted from RDS using Sqoop, then processed through an ETL pipeline to ensure accurate and efficient data flow processing.

Data Modeling Strategy
An entity-relationship (ER) diagram is created to illustrate data relationships, providing a clear understanding of data flow and interconnections.

ETL Pipeline Implementation
The data undergoes extraction, transformation, and loading into Redshift Data Warehouse using Glue for analysis.

# Data Engineering
Data Importing
Spar Nord Bank ATM transaction data is extracted from RDS using Sqoop.

Data Cleaning Procedure
Utilizing PySpark on Google Colab, we clean the data to eliminate duplicates, handle missing values, and correct data types.

ETL Operations
Extract, Transform, Load (ETL) operations are performed to prepare the data for analysis. The transformed data is loaded into the Redshift Data Warehouse using Glue.

# Data Analytics and Visualization
Data Analytics Techniques
Amazon Redshift, a cloud-based data warehouse, enables rapid querying and processing of large datasets for data analysis.

Key Insights Extraction
Our analysis reveals trends in ATM usage by time of day, day of the week, and location. We also identify correlations between ATM usage and weather conditions.

Data Visualization Methods
Line charts, bar charts, and other visualizations effectively communicate trends and insights discovered through data analysis.

# Summary and conclusion
Through comprehensive data analysis, our project provides valuable insights into Spar Nord Bank's ATM transaction data:

Customer Behavior Insights: Peak transaction times and preferred payment methods are identified, enabling informed decision-making processes.

Cost-Saving Opportunities: Non-peak time periods are pinpointed as optimal for ATM refills, potentially leading to cost savings on refilling operations.

Our project underscores the significance of data-driven optimization in enhancing customer experience, optimizing operations, and achieving cost efficiency.

project code and findings of the insights derived from the Spar Nord Bank ATM transaction data are uploaded.
