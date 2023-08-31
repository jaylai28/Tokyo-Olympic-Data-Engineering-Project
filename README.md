# Tokyo-Olympic-Data-Engineering-Project
Tokyo Olympic Data Engineering Project. This is a data engineering project focused on performing data cleansing, transformation and analysing on Tokyo Olympic data. The project uses AWS services, Azure Databricks and Tableau for data processing, analysis, and visualisation.

Starting with data ingestion into an Amazon S3 bucket, the project moves to Databricks for data transformation. Processed data is then stored back in a transformed folder in the S3 bucket. AWS Glue Crawler organizes the data and generates an AWS Athena table, facilitating comprehensive analysis.

The data ingestion ingests the data sets into Amazon S3 bucket. It then be used to load into Databricks for data transformation. The data are then loaded back into the transformed data folder in AWS S3 bucket. 

AWS Glue Crawler then organizes and crawls the data from the S3 bucket and creates a table in Glue Data Catalog. AWS Athena is used for detailed analysis using SQL Query. This comprehensive process showcases the journey from data ingestion and transformation to storage and analysis. Finally, Tableau is used to create the dashboard.

![Tokyo Olympic Chart](https://github.com/jaylai28/Tokyo-Olympic-Data-Engineering-Project/assets/69461406/f91bb72e-2ae7-4401-9c4c-608975556d9b)



# Tokyo Olympic Dashboard Overview
![Tokyo Olympic Image](https://github.com/jaylai28/Tokyo-Olympic-Data-Engineering-Project/assets/69461406/3aca72b5-61b8-456a-9bbe-875bdf296249)
