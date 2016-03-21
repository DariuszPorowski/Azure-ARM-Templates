# Domain join a VM to an existing domain

This template create new Windows Server VM with one data disk and join it to an existing ADDS domain. The template requires a domain controller to already be setup. Virtual Network and Storage Accounts on Azure site must exist.
The template is based on https://github.com/Azure/azure-quickstart-templates/tree/master/201-vm-domain-join

### REQUIREMENTS
1. Existing Active Directory Domain Services domain controller.
2. Existing Storage Accounts in the same Resource Group where VM will be created.
3. Existing Virtual Network could be in diffrent Resource Group.
4. Deploy to the Virtual Network with ADDS domain controller - could be diffrent subnet. 

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDariuszPorowski%2FAzure-ARM-Templates%2Fmaster%2Fvm-domain-join%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FDariuszPorowski%2FAzure-ARM-Templates%2Fmaster%2Fvm-domain-join%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>