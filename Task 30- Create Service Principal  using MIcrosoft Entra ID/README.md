# Task 30: Create Service Principal using Microsoft Entra ID

## Objective
Create a Service Principal in Microsoft Entra ID to enable secure authentication for applications, automation tools, and DevOps pipelines to access Azure resources.

---

## Steps

### Step 1: Login to Azure Portal
- Open https://portal.azure.com
- Sign in with your Azure account credentials

---

### Step 2: Navigate to Microsoft Entra ID
- In the search bar, type: Microsoft Entra ID
- Click Microsoft Entra ID

---

### Step 3: Open App Registrations
- In the left menu, click App registrations
- Click + New registration

---

### Step 4: Register Application

Enter the following details:

- Name: sp-rbactest
- Supported account types: Accounts in this organizational directory only (Single tenant)

Leave Redirect URI empty.

Click Register

---

### Step 5: Copy Application Details

After registration, go to Overview tab and copy:

- Application (client) ID
- Directory (tenant) ID

These are used for authentication in automation and DevOps tools.

---

### Step 6: Create Client Secret

- Click Certificates & secrets
- Click + New client secret
- Enter Description: sp-secret
- Select Expiration: 6 months
- Click Add

Copy the secret value immediately.

---

## Verification

To verify the Service Principal creation:

- Go to Microsoft Entra ID → App registrations
- Confirm that sp-rbactest is listed

---

## Key Learning

- Learned how to create Service Principal
- Understood application identity in Azure
- Learned authentication setup for automation and DevOps

---

## Result

Successfully created a Service Principal in Microsoft Entra ID.

---

