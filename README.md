InstaCart Data Pipeline built on Microsoft Azure.
 I aimed to build something that covers the full lifecycle of data: extraction, transformation, and loading — all using cloud-native tools on Azure.
🔧 What I built:
 A data pipeline that pulls data from the GitHub API, processes it using Azure Functions, stores raw and transformed data in Azure Data Lake Storage Gen2, and makes it queryable via Azure Synapse Analytics and Serverless SQL pools.
🧩 Key Azure components used:
Python for API data extraction
Azure Functions for serverless ETL
Azure Logic Apps / Timer Triggers for automation
Azure Data Lake (ADLS Gen2) for storing raw + processed data
Event Grid Triggers to initiate transformation when new data lands
Azure Data Factory for orchestration and pipeline management
Azure Synapse Analytics for schema inference and querying
Serverless SQL Pool for running SQL-based analytics
Azure Monitor for observability
![chart](https://github.com/user-attachments/assets/dc5e6c10-6962-46ee-880e-a426f0ee0d03)

![chart2](https://github.com/user-attachments/assets/5e74f2bd-02cc-4d8d-8899-d120270adb5d)
