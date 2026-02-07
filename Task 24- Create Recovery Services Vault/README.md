# Task-24: Create Recovery Services Vault

## Objective
Create a Recovery Services Vault in Azure to store Virtual Machine backups and simulate VM migration and disaster recovery.

---

## Prerequisites
- Azure Free Tier account
- Resource Group created (Example: rg-demo)
- Source Virtual Machine available
- Access to Azure Portal

---

## Steps

### Step 1: Sign in to Azure Portal
Go to: https://portal.azure.com  
Sign in with your Azure account.

### Step 2: Search for Recovery Services Vault
In the search bar, type:
Recovery Services Vaults  
Click on **Recovery Services Vaults**

### Step 3: Click Create
Click **+ Create**

### Step 4: Configure Vault Details
Enter the following:

- Subscription: Select your subscription  
- Resource Group: `rg-demo`  
- Vault Name: `Migration-Recovery-Vault`  
- Region: `Central India`  

Click **Review + Create**

### Step 5: Create Vault
Click **Create**  
Wait for deployment to complete  
Click **Go to resource**

### Step 6: Verify Vault
Verify vault dashboard opens successfully.  
Ensure options like **Backup, Backup Items, Backup Policies, Site Recovery** are visible.

---

##  Output
Recovery Services Vault created successfully.

Example:
- Vault Name: Migration-Recovery-Vault  
- Resource Group: rg-demo  
- Region: Central India  
- Status: Active  

