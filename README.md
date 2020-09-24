# Automation-to-deploy-Azure-Data-Factory-Lab 
This script will deploy and configure all the resources need for the Azure Data Factory lab. Change data source path for uploading to BLOB and ARM template based on your scenario. Go through user document to get a complete diretion. We will be performing the following tasks by running a PowerShell file to configure and deploy Azure resources needed. This includes

•	Azure storage account
•	Azure SQL Server
•	Azure Logic App
•	Azure Data warehouse
•	Office365 API connection
•	Azure Data Factory

The following other changes will also be performed by the script:
•	Create containers needed on the Azure Storage account
•	Upload txt, csv, and database backups to the Azure Storage account
•	Restore bacpacs from the Azure Storage account to the Azure SQL Server
•	Create Schema on the Azure SQL DW DB
