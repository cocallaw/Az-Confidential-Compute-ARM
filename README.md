# Azure Confidential Compute VM Deployment with ARM Templates

This repository contains ARM templates for deploying Azure Confidential Compute machines, configured with Confidential Disk Encryption and Customer Managed Key(CMK) encryption.

The templates will deploy the following resources in Azure:
- Azure Virtual Network 
- Azure Key Vault
- Azure Disk Encryption Set
- Azure Bastion (Optional)
- Azure Confidential Compute VM 

<br>

|                                                                                                        **Single VM**                                                                                                       |                                                                                                      **Multiple VMs**                                                                                                      |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| [![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcocallaw%2FAz-Confidential-Compute-ARM%2Fmain%2FSingle-VM%2Fazuredeploy.json) | [![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcocallaw%2FAz-Confidential-Compute-ARM%2Fmain%2FMultiple-VMs%2Fazuredeploy.json) |