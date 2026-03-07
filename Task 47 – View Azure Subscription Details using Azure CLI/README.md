# Task 47 – View Azure Subscription Details using Azure CLI

This task verifies the current Azure subscription and account information using Azure CLI in Cloud Shell.

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

Run the following command to view subscription details:

```bash
az account show
### Step 4 – Review the Output

The command displays information such as:

- **Environment Name**
- **Subscription ID**
- **Subscription Name**
- **Tenant ID**
- **User Details**

This confirms which Azure subscription is currently active.
