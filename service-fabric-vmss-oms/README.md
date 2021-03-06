# Deploy Azure Service Fabric Cluster and enable monitoring for Service Fabric and VMSS using OMS Log Analytics

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fazure%2Fazure-quickstart-templates%2Fmaster%2Fservice-fabric-vmss-oms%2F%2Fazuredeploy.json) 
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fservice-fabric-vmss-oms%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template will deploy an Azure Service Fabric Cluster together with an OMS Log Analytics workspace, adds the diagnostic storage account into OMS for monitoring and insights and enables the OMS Gallery Solution for Service Fabric. In addition, each VM Scale Set instance will get connected to the OMS Workspace.

The OMS Gallery Service Fabric solution uses Azure Diagnostics data from your Service Fabric VMs, by collecting this data from your Azure WAD tables. 
Log Analytics then reads Service Fabric framework events, including Reliable Service Events, Actor Events, Operational Events, and Custom ETW events. 
The Service Fabric solution dashboard shows you notable issues and relevant events in your Service Fabric environment.


