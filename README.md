# Migration-project-01


# Description:

Building a data pipeline to move all the tables from a specific database in on-perm SQL server to ADLS GEN 2 (blob storage) in AZURE.


# Resources used:
1. Microsoft SQL SERVER
2. Microsoft SQL server management studio(SSMS)
3. Microsoft Azure
4. AdventureWorks dataset lightweight version (https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver17&tabs=ssms)
5. Azure Data Factory
6. GitHub


# Prerequisites:
1. Must have Azure Subscription
2. Java Runtime Environment (I've faced a challenge that before tables ingestion self-hosted Integration Runtime needs JRE to convert table to PARQUET format)


# Services used in Azure
1. Storage Account
2. Azure Data factory
3. Azure Key Vault
4. Azure Databricks
5. Azure Synapse


# Things Learned
1. Configuring Azure services.
2. Giving access to user and services for storage.
3. Creating pipelines
4. Creating Datasets
5. Ingesting data through linked services
6. Using parameters in pipeline
7. Integration runtimes in adf
8. Using different activities in pipelines some are copy data, lookup and forEach.
9. Dynamically providing folder name and file name while ingesting.
