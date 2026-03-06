# Task 43 – Enable Backup for Virtual Machine using Azure Backup

## Objective
Enable backup for an Azure Virtual Machine using Azure Backup through a Recovery Services Vault to protect VM data and ensure recovery in case of failure.

---

## Prerequisites
Before starting this task, ensure the following resources exist:

- An active Azure Subscription  
- A Virtual Machine  
- A Recovery Services Vault  

These resources will be used to configure backup.

---

## Steps 

### Step 1 – Sign in to Azure Portal
1. Open the Azure Portal.
2. Login with your Azure account.

---

### Step 2 – Open Recovery Services Vault
1. In the search bar, type **Recovery Services Vault**.
2. Select your existing vault from the list.

---

### Step 3 – Start Backup Configuration
1. Inside the vault, click **Backup**.
2. In **Where is your workload running?**, choose:
   - Azure
3. In **What do you want to back up?**, choose:
   - Virtual Machine
4. Click **Backup**.

---

### Step 4 – Select Virtual Machine
1. Click **Select Virtual Machines**.
2. Choose the VM you want to protect.
3. Click **Select**.

---

### Step 5 – Configure Backup Policy
1. Choose a **Backup Policy**.

Default settings include:
- Daily backup schedule
- Retention period for recovery points

2. Click **Enable Backup**.

---

### Step 6 – Verify Backup Configuration
1. Go to **Backup Items**.
2. Select **Azure Virtual Machine**.
3. Verify that your VM appears in the list.

This confirms backup protection is enabled.

---

## Conclusion

In this task, we successfully configured Azure Backup for a virtual machine using a Recovery Services Vault. This ensures that the VM can be restored in case of accidental deletion, system failure, or data loss.
