# Task 27: Assign Reader Role to User using RBAC

## Objective
Assign the Reader role to a user using Azure Role-Based Access Control (RBAC). The Reader role allows the user to view Azure resources but does not allow making any changes.

---

## Steps

### Step 1: Login to Azure Portal
- Open https://portal.azure.com
- Sign in with your Azure account credentials

---

### Step 2: Navigate to Resource Groups
- In the search bar, type: Resource groups
- Click on Resource groups
- Select your resource group (example: rg-rbactest)

---

### Step 3: Open Access Control (IAM)
- In the left menu of the resource group, click Access control (IAM)
- Click + Add
- Select Add role assignment

---

### Step 4: Select Reader Role
- In the Role tab, select Reader
- Click Next

---

### Step 5: Select User
- Click Select members
- Search and select testuser1
- Click Select

---

### Step 6: Assign Role
- Click Review + assign
- Click Review + assign again to confirm

---

## Result

Successfully assigned Reader role to the user using RBAC.

---
## Verification

To verify the role assignment:

- Go to Resource Group → Access control (IAM)
- Click Role assignments tab
- Confirm that testuser1 has Reader role

---
