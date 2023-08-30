# Tokyo-Olympic-Data-Engineering-Project
Tokyo Olympic Data Engineering Project. This is a data engineering project focused on performing data cleansing, transformation and analysing on Tokyo Olympic data. The project uses AWS services, Azure Databricks and Tableau for data processing, analysis, and visualisation.

Starting with data ingestion into an Amazon S3 bucket, the project moves to Databricks for data transformation. Processed data is then stored back in a transformed folder in the S3 bucket. AWS Glue Crawler organizes the data and generates an AWS Athena table, facilitating comprehensive analysis.

The data ingestion ingests the data sets into Amazon S3 bucket. It then be used to load into Databricks for data transformation. The data are then loaded back into the transformed data folder in AWS S3 bucket. 

AWS Glue Crawler then organizes and crawls the data from the S3 bucket and creates a table in Glue Data Catalog. AWS Athena is used for detailed analysis using SQL Query. This comprehensive process showcases the journey from data ingestion and transformation to storage and analysis. Finally, Tableau is used to create the dashboard.

![Tokyo Olympic Flow Chart](https://github.com/jaylai28/Tokyo-Olympic-Data-Engineering-Project/assets/69461406/3fe11e45-3163-4c57-ad28-d4d4932a36c3)
