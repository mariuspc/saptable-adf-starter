[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmariuspc%2Fsaptable-adf-starter%2Fmaster%2Fazuredeploy.json)


This template creates a data factory that ingests data from a configurable list of SAP table entities into Azure Blob Storage. When you deploy this Azure Resource Manager template, the following entities get created: 

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
1. Open the deployed data factory and enter the SAP Table connection details
2. Validate all existing linked services and datasets


## TODO
- Azure Key Vault integration
- Deploy behind vnet
- use Managed Identify to access Azure Blob and the metadata database
