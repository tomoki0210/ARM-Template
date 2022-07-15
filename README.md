# Deploy a MySQL Server

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fgithub.com%2Ftomoki0210%2FARM-Template%2Fblob%2Fmain%2Fazuredeploy.json)

[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fapplication-workloads%2Fmysql%2Fmysql-standalone-server-ubuntu%2Fazuredeploy.json)

This template uses the Azure Linux CustomScript extension to deploy a MySQL server. It creates an Ubuntu VM, does a silent install of MySQL server, version:5.6

The root password is defined by yourself during the deployment.

The MySQL server database can be accessed only from localhost by default, you should update the privileges settings based on your own requirement.

`Tags: Microsoft.Storage/storageAccounts, Microsoft.Network/publicIPAddresses, Microsoft.Network/virtualNetworks, Microsoft.Network/networkInterfaces, Microsoft.Compute/virtualMachines, Microsoft.Compute/virtualMachines/extensions, CustomScript`
