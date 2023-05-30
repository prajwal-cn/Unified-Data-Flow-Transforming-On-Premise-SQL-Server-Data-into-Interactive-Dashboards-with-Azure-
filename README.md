# Unified Data Flow: Transforming On-Premise SQL Server Data into Interactive Dashboards with Azure Services

## Overview
This project demonstrates a comprehensive end-to-end data pipeline, utilizing Azure services to transform data from an on-premise SQL Server database into interactive dashboards with Microsoft Power BI. The pipeline involves ingestion, storage, transformation, and visualization of the data, incorporating various Azure services for seamless integration and enhanced analytics capabilities.

## Steps

### Step 1: Ingesting Tables from On-Premise SQL Server Database
- Use Azure Data Factory to connect to the on-premise SQL Server database.
- Configure data ingestion pipelines in Azure Data Factory to extract the required tables.
- Utilize Azure Data Factory's managed service to facilitate the movement and transformation of data.

### Step 2: Storing Data in Azure Data Lake
- After extracting the data from the SQL Server database, store it in Azure Data Lake.
- Azure Data Lake provides scalable and secure cloud-based storage for big data analytics.

### Step 3: Transforming the Raw Data with Azure Databricks
- Leverage Azure Databricks, an Apache Spark-based analytics platform, for data transformation.
- Use Databricks to clean and process the raw data, ensuring it is in the most refined and usable form.

### Step 4: Loading Clean Data into Azure Synapse Analytics
- Employ Azure Synapse Analytics, a cloud-based analytics service, for loading and further analysis of the clean data.
- Azure Synapse Analytics combines data warehousing and big data capabilities, providing a unified data exploration and visualization experience.

### Step 5: Building an Interactive Dashboard with Power BI and Azure Synapse Analytics
- Integrate Microsoft Power BI with Azure Synapse Analytics to create an interactive dashboard.
- Utilize Power BI's capabilities to build visualizations, reports, and dashboards that offer valuable insights into the data processed by Azure Synapse Analytics.

### Step 6: Monitoring and Governance with Azure Active Directory (AAD) and Azure Key Vault
- Utilize Azure Active Directory (AAD) for monitoring and governance purposes, ensuring secure access to the project's components.
- Leverage Azure Key Vault to securely store and manage sensitive information such as passwords, API keys, and encryption keys.

##
