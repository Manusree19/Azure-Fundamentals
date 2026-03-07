# Task 50 – List Azure Resources using Azure PowerShell

This task retrieves all Azure resources in the subscription using Azure PowerShell in Cloud Shell.

---

## Steps

### Step 1 – Sign in to Azure Portal
1. Open the Azure Portal.
2. Login with your Azure account.

---

### Step 2 – Open Azure Cloud Shell
1. Click the **Cloud Shell** icon at the top of the Azure Portal.
2. Select **PowerShell** as the shell environment.

---

### Step 3 – Run PowerShell Command

Run the following command to list Azure resources:

```powershell
Get-AzResource
---

###  Step 4 – Review the Output

The command displays information such as:

Resource Name

Resource Group Name

Resource Type

Location

This confirms the resources currently deployed in the Azure subscription.
