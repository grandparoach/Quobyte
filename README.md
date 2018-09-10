# Quobyte
Automated provisioning for Quobyte servers

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgrandparoach%2FQuobyte%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template lets you create an N node Quobyte File System. You can provision 2, 4, 6, 8 or 10 nodes in a cluster. These machines will be placed into the same Availability Set.  There are no public IP addresses, so it must be installed onto an existing Virtual Network.  The number and size of the attached disks are specified as input parameters.  
