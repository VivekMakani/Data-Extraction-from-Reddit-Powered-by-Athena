# Data-Extraction-from-Reddit-Powered-by-Athena
Developed an ETL pipeline for Reddit data using Apache Airflow, Docker, and Python, facilitating efficient data extraction and storage into AWS S3, streamlining insight generation.



![Architecture_Reddit_pipeline](https://github.com/user-attachments/assets/6f15de5c-62b3-4145-a4ea-5a7ed072b50b)




1. Reddit API: Source of the data.
2. Apache Airflow & Celery: Orchestrates the ETL process and manages task distribution.
3. PostgreSQL: Temporary storage and metadata management.
4. Amazon S3: Raw data storage.
5. AWS Glue: Data cataloging and ETL jobs.
6. Amazon Athena: SQL-based data transformation.
7. Amazon Redshift: Data warehousing and analytics.

Prerequisite:

1. AWS Account with appropriate permissions for S3, Glue, Athena, and Redshift.
2. Reddit API credentials.
3. Docker Installation
4. Python 3.9 or higher

