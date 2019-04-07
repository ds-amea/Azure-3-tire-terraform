# Azure-3-tire-terraform

## Overview:
   This project is created for Azure best practice application deployment and securing it with Trend Micro deep security. Terraform web config file consists Deep security script to deploy agent in autoscaling instances.
   
## Azure Resources deploy
   Terraform will deploy following Azure resources.
   1) vNET with 3 subnets
   2) 2 scaleset with LB and LB backend pools
   3) 1 Jump server in DMZ and 1 DB server in private subnet
   4) 1 resource group and NSG for web traffic
   5) apache and basic web page configuration on scaleset servers.
