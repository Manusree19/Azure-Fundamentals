# Task 49 – Verify Azure Context using Azure PowerShell

This task verifies the current Azure subscription context using Azure PowerShell in Cloud Shell.

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

Run the following command to view the current Azure context:

```powershell
 Get-AzContext

###  Step 4 – Review the Output

The command displays information such as:

Account

Subscription Name

Subscription ID

Tenant ID

Environment

This confirms the active Azure subscription and account context.
