# AWS_ETL_Project

In this project, I built a fully automated, serverless ETL pipeline that enables data analysts to query and analyze nested JSON data in a relational, tabular format. The pipeline is triggered automatically whenever new data is uploaded to an Amazon S3 bucket. It processes the data using AWS Lambda and stores the transformed output in a Parquet format for efficient querying in Amazon Athena.

The diagram below outlines each step of the pipeline, making it easy to understand and replicate. For demonstration, I used a dummy Amazon orders dataset representing purchases made by 12 customers.

<img width="2468" height="1046" alt="image" src="https://github.com/user-attachments/assets/7254bd74-09b9-4e5d-a4c1-3cba0bb48dfb" />
