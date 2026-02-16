# Task 26: Create Security Group in Microsoft Entra ID

## Objective
Create a security group in Microsoft Entra ID to manage multiple users efficiently and assign RBAC roles at the group level instead of assigning roles individually.

---

## Steps

### Step 1: Login to Azure Portal
- Open https://portal.azure.com
- Sign in with your Azure account credentials

---

### Step 2: Navigate to Microsoft Entra ID
- In the search bar, type: Microsoft Entra ID
- Click on Microsoft Entra ID

---

### Step 3: Open Groups Section
- In the left menu, click Groups
- Click + New group

---

### Step 4: Configure Group Details

Enter the following details:

- Group type: Security
- Group name: developers
- Group description: Security group for developers

Click Create

---

### Step 5: Add User to Group

After creating the group:

- Open the developers group
- Click Members
- Click + Add members
- Select testuser1
- Click Select

---
## Result

Successfully created a security group and added user to the group.

---

## Verification

To verify the group creation and membership:

- Go to Microsoft Entra ID → Groups
- Open developers group
- Click Members
- Confirm that testuser1 is listed

---


## Author
Your Name
