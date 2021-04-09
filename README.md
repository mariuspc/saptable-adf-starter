[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmariuspc%2Fsaptable-adf-starter%2Fmaster%2Fazuredeploy.json)


This template creates an Azure Data Factory that ingests data from a configurable list of SAP table entities into Azure Blob Storage. When you deploy this Azure Resource Manager template, the following entities get created: 

- Azure SQL Database (metadata database)
- Azure Blob Storage
- Azure Data Factory
- Azure Storage linked service 
- Azure SQL Database linked service
- SAP Table linked service
- Azure SQL Database input dataset
- SAP Table input dataset
- Azure Blob output datasets
- Driver and worker pipelines

## Next steps
1. Open the deployed Data Factory 
2. Configure or link the [Integration Runtime](https://docs.microsoft.com/en-us/azure/data-factory/connector-sap-table) needed to access the SAP environment
3. Update the [SAP Table Linked Service](https://docs.microsoft.com/en-us/azure/data-factory/connector-sap-table) with the relevant connection details
4. Validate all other linked services and datasets
5. Check and validate the metadata configuration 


## TODO
- Azure Key Vault integration
- Deploy behind vnet
- Use Managed Identify to access the Azure Blob and the metadata database
- Integration with CDM format
- Add Synapse Analytics to the deployment 