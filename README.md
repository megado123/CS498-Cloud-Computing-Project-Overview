# CS498-Cloud-Computing-Project-Overview

## Project Status

| Activity      | Planned Completion   |Status      | Comments      |
| ------------- |----------------------|------------|:--------------|
| Development Platform – Exploration and Finalization |	Week 3, February| Complete| Microsoft Azure |
| Load Balancer – AWS EC2, Microsoft Azure – Exploration | Week 3, February| Complete| Azure Load Balancer |
| Study on Python library pymzML | Week 3, February| Complete| Will not be used |
| Getting raw sample data for reference| Week 3, February| Complete||
| NIST data initial analysis and review	| Week 4, February|	Complete| R script created to clean data |
| Azure App Service – Self study | Week 4, February|	In Progress	Install Python runtime, Install dependencies |
| Set up Project in Azure portal	| Week 4, February| Complete ||	
| Azure Data Factory – Set up copy utility for one-time load| Week 4, February| Complete ||	
| Document DB Data Migration	| Week 4, February| Complete ||
| NIST data conversion to JSON format| Week 4, February| Complete ||	
| Load reference data using JSON, query data and check data |Week 1, March |Complete	| Data loaded successfully|
| Machine learning library set up in Azure Workspace, Explore and set up AzureML	| Week 1, March	| In Progress |Import to workspace completed. Getting some issues in accessing the data |
| Azure AD Tenant set up, Create new Azure AD tenant, Create dummy users and passwords, User authentication|	Week 2, March |In Progress |Not huge priority since the Azure AD integration for this to be used in a corporation would require Azure AD integration with a specific tenant, and currently our API is secured through a managed expiring key |
| Connect the Cosmos DB interface with Apache Spark, Refer pyDocumentDB SDK |Week 3, March |In Progress |Successful with HDI, achieved success currently with Azure Data Bricks which appears to be on Microsoft’s strategic road map |
| Azure Container Services set up |Week 3, March |In Progress | For Node management|
| Create Web Service in Azure App Service, JSON transmission for REST service| Week 4, March |In Progress |Python is considered an experimental language, currently attempting to add values into Cosmos DB and then use the insertion to trigger the analysis of the input data, however the current response time for the insertion into the Cosmos DB is at 3 seconds |
| Get Python function built for reference match, Unit test the function locally within Azure | Week 1, April |In Progress |Issue with data types in Cosmos DB |
| Integrate Web Service to Azure AD tenant and Azure Spark service | Week 2, April | Yet to Start |	
| Integration test| Week 2, April| Yet to Start|
| Load test for load balancing |Week 3, April| Yet to Start|
| Project Documentation	| Week 4, April| Yet to Start|


## Project Data Flow

![](https://github.com/megado123/CS498-Cloud-Computing-Project-Overview/blob/master/images/CS498DataFlow.png)
