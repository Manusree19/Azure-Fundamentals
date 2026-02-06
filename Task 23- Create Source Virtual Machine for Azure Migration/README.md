# Task-23: Create Source Virtual Machine for Azure Migration

## Objective
Create an Azure Virtual Machine to simulate an on-premises server, which will be used as the source for Azure migration.

---

## Prerequisites
- Azure Free Tier account
- Azure Migrate Project created
- Discovery tool enabled

---

## Steps

1. Sign in to Azure Portal  
   https://portal.azure.com

2. Search for:
   `Virtual Machines`

3. Click:
   `Create` → `Azure Virtual Machine`

4. Configure basic settings:

   Resource Group:
   `Azure-Migration-RG`

   Virtual Machine Name:
   `Source-VM`

   Region:
   `Central India`

   Image:
   `Windows Server 2019 Datacenter`
   OR
   `Ubuntu Server 22.04 LTS`

   Size (Free Tier):
   `Standard B1s`

---

5. Configure administrator account:

   Username:
   `azureuser`

   Password:
   `Create strong password`

---

6. Configure inbound ports:

   Select:
   `Allow RDP (3389)` for Windows  
   OR  
   `Allow SSH (22)` for Linux  

---

7. Click:
   `Review + Create`

8. Click:
   `Create`

Wait for deployment to complete.

---

## Output

Virtual Machine created successfully.

VM Name:
`Source-VM`

Status:
`Running`

---

---
