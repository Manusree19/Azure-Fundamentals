# Task 48– List Resource Groups using Azure CLI

This task lists all resource groups available in the Azure subscription using Azure CLI in Cloud Shell.

---

## Steps

### Step 1 – Sign in to Azure Portal
1. Open the Azure Portal.
2. Login with your Azure account.

---

### Step 2 – Open Azure Cloud Shell
1. Click the **Cloud Shell** icon at the top of the Azure Portal.
2. Select **Bash** to use Azure CLI.

---

### Step 3 – Run Azure CLI Command

Run the following command to list all resource groups:

```bash
az group list --output table
Step 4 – Review the Output

The command displays a table containing information such as:

Resource Group Name

Location

Provisioning State

This confirms all resource groups available in the Azure subscription.
