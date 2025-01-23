# Spotify_Data_Pipe_Snowflake

### Introduction
It is a project build using ETL(Extract, Transform, Load) pipeline using Spotify API on AWS. The pipeline will retrieve data from Spotify API, transform it to a desired format, and load into AWS S3(Data Storage).

### Architecture
![Architecture Diagram](https://github.com/user-attachments/assets/4a6017ba-6d0d-4fa1-b25b-7aee0b99e600)



### Services Used
1. **AWS S3(Simple Storage Service):** AWS S3 is a highly saclable object storage service used for storing and retrieving any amount of data from anywhere using web. It is commonly used to store and distribute large files.
   
2. **AWS Lambda:** AWS Lambda is a serverless computing service that lets you run code without managing servers.
   
3. **Cloud Watch:** AWS Cloudwatch is a monitoring service for AWS Resources and the applications you run on them. It is used to collect and tracks metrics, collect and monitor log files and set alarms.

4. **AWS Data Catalog:** AWS Data Catalog is a centralized metadata repository for all your data assets across various data sources. 

5. **AWS GLue Crawler:**  AWS Data Catalog consists of AWS Glue Crawler which crawls the data sources and identifies data formats, infer schemas and create AWS Glue Data Catalog.

6. **AWS Athena:**  Amazon Athena is a interactive query service that makes it easy to analyze data stored in S3 using standard SQL. It is also used to analyze stored in Glue Data Catalog.

7.  **Snowflake:** Snowflake is a cloud-based data warehouse platform that allows users to store, analyze, and exchange data securely.

8. **PowerBI:** Power BI is a business analytics service by Microsoft that allows organizations to connect to various data sources, transform and clean data, create interactive visualizations, and share insights with others.





### Dashboard
![Architecture Diagram](https://github.com/user-attachments/assets/e8b4d9e6-2fb9-4cd5-8212-2e38802198d7)
