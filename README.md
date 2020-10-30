# Power BI Visualization for Azure Synapse SQL Pool Database Management Views

This repo provides Power BI Desktop template that can be used to visualize Azure Synapse DMVs. DMVs provide more insights into the internals of Azure Synapse Pools. This helps to better understand the performance problems, tune distribution and understand overall performance of the database. 

The template connects to more than 30 DMVs and Azure Monitor metrics. The template provides some baseline visuals which can be extended further. 


<img src="https://github.com/anildwarepo/azuresynapsedmvs/raw/main/imgs/DMV%20relationship.png" width="500">


### DMV Visualization samples

#### Nodes

<img src="https://github.com/anildwarepo/azuresynapsedmvs/raw/main/imgs/NodeCount.png" width="500">

#### Storage

<img src="https://github.com/anildwarepo/azuresynapsedmvs/raw/main/imgs/Storage.png" width="500">

#### Table Distribution

<img src="https://github.com/anildwarepo/azuresynapsedmvs/raw/main/imgs/Table%20Distribution.png" width="500">


### Getting Started

#### Pre-requisites

- Access to Azure Synapse Workspace
- Access to Azure Monitor Metrics
- Power BI Desktop installed from local computer which has network connectivity to Azure Synapse SqlPool(incase of Private Link)

#### 

Download Synapse-DMVs.pbit Power BI Desktop template and launch it with Power BI Desktop. 
Provide inputs to the parameters
- subscriptionId - Azure Subscription where Synapse Workspace is provisioned
- resourceGroup - Resource Group where Synapse workspace is provisioned
- synapseWorkspaceName - Synapse workspace name
- sqlPoolName - Synapse SQLPool Name
- synapseEndPoint - <sqlPoolName>.sql.azuresynapse.net

<img src="https://github.com/anildwarepo/azuresynapsedmvs/raw/main/imgs/TemplateParamaters.png" width="500">

