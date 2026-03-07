# Task 46- Create Azure Load Balancer using Cloud Shell

## Objective
Create an Azure Load Balancer using Azure CLI in Azure Cloud Shell to distribute incoming traffic across backend resources and improve availability.

## Prerequisites
- Azure Subscription
- Existing Resource Group
- Access to Azure Cloud Shell
- Azure CLI

## Steps

### 1. Create Public IP Address

```bash
az network public-ip create \
--resource-group rg-self-healing-cloud \
--name lb-public-ip \
--sku Standard \
--location centralindia
### 2.Create Load Balancer
az network lb create \
--resource-group rg-self-healing-cloud \
--name myLoadBalancer \
--sku Standard \
--public-ip-address lb-public-ip \
--frontend-ip-name myFrontEnd \
--backend-pool-name myBackEndPool
### 3.Verify Load Balancer
az network lb list --output table
### Expected output
| Name           | ResourceGroup         | Location     |
| -------------- | --------------------- | ------------ |
| myLoadBalancer | rg-self-healing-cloud | centralindia |
