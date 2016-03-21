# Create a VM form specialized VHD in an existing Virtual Network

This template creates a VM from a specialized VHD and let you connect it to an existing Virtual Network that can reside in another Resource Group then the Virtual Machine. Network Security Group for the VM will be created with RDP allow rule form the Internet on the TCP/3389 port for Windows VM or SSH allow rule form the Internet on the TCP/22 port for Linux VM.
The template is based on https://github.com/Azure/azure-quickstart-templates/tree/master/201-specialized-vm-in-existing-vnet

### REQUIREMENTS
1. URL to the existing VHD file in ether a premium or standard storage account.
2. Name of the existing Virtual Network and Subnet you want to connect the new virtual machine to. 
3. Name of the Resource Group that the Virtual Network resides in.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDariuszPorowski%2FAzure-ARM-Templates%2Fmaster%2Fvm-from-specialized-vhd-in-existing-vnet%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FDariuszPorowski%2FAzure-ARM-Templates%2Fmaster%2Fvm-from-specialized-vhd-in-existing-vnet%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>