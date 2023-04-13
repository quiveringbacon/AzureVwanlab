# Azure Vwan lab

This just creates a vwan and a couple of spoke vnets with VM's connected to the vhub. You'll be prompted for the resource group name, location where you want the resources created, your public ip and username and password to use for the VM's. NSG's are placed on the default subnets of each vnet allowing RDP access from your public ip.

The topology will look like this:

![wvanlab](https://user-images.githubusercontent.com/128983862/231876978-baf5a181-063b-47ce-b437-1e15e2f25bc1.png)

