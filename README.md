# Azure Vwan lab

This just creates a vwan and a hub and a couple of spoke vnets with VM's connected to the vhub. You'll be prompted for the resource group name, location where you want the resources created, your public ip and username and password to use for the VM's. NSG's are placed on the default subnets of each vnet allowing RDP access from your public ip. This also creates a logic app that will delete the resource group in 24hrs.

The topology will look like this:

![wvanlab](https://user-images.githubusercontent.com/128983862/232787597-d47466ed-0603-4ef9-bd02-ced80fe2d406.png)

You can run Terraform right from the Azure cloud shell by cloning this git repository with "git clone https://github.com/quiveringbacon/AzureVwanlab.git ./terraform".

Then, "cd terraform" then, "terraform init" and finally "terraform apply -auto-approve" to deploy.
