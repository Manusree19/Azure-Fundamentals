# Task 31: Assign Contributor Role to Service Principal using RBAC

## Objective
Assign the Contributor role to the Service Principal using Azure Role-Based Access Control (RBAC). This allows the Service Principal to create, manage, and delete Azure resources within the assigned scope.

---

## Steps

### Step 1: Login to Azure Portal
- Open https://portal.azure.com
- Sign in with your Azure account credentials

---

### Step 2: Navigate to Resource Groups
- In the search bar, type: Resource groups
- Click Resource groups
- Select your resource group (example: rg-rbactest)

---

### Step 3: Open Access Control (IAM)
- In the left menu, click Access control (IAM)
- Click + Add
- Select Add role assignment

---

### Step 4: Select Contributor Role
- In the Role tab, select Contributor
- Click Next

---

### Step 5: Select Service Principal
- Click Select members
- Search and select sp-rbactest (Service Principal created in Task 30)
- Click Select

---

### Step 6: Assign Role
- Click Review + assign
- Click Review + assign again to confirm

---
## Result

Successfully assigned Contributor role to the Service Principal.

---
## Verification

To verify the role assignment:

- Go to Resource Group → Access control (IAM)
- Click Role assignments tab
- Confirm that sp-rbactest has Contributor role

---


## Author
Your Name
