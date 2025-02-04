# Create a Microsoft Endpoint Configuration Manager Technical Preview Lab environment in Azure

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnickselvaggio%2Fazure-quickstart-templates%2Fmaster%2Fapplication-workloads%2Fsccm%2Fsccm-technicalpreview%2Fazuredeploy.json)
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnickselvaggio%2Fazure-quickstart-templates%2Fmaster%2Fapplication-workloads%2Fsccm%2Fsccm-technicalpreview%2Fazuredeploy.json)

## Description

This template deploys the latest Microsoft Endpoint Configuration Manager (ConfigMgr) Technical Preview with following configuration: 

* a new AD domain controller. 
* a standalone primary site with SQL Server, ADK and ConfigMgr installed. ConfigMgr is the latest Technical Preview release.
* a remote site system server to host managemenent point and distribution point. 
* sccm clients.(Options)

Each VM has its own public IP address and is added to a subnet protected with a Network Security Group, which only allows RDP from the Internet. 

Each VM has a private network IP which is for ConfigMgr communication. 

For more information, Visit [Create a Configuration Manager lab in Azure](https://docs.microsoft.com/en-us/configmgr/core/get-started/azure-template)
