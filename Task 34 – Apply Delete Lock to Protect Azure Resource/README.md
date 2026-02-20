# Task 34 – Apply Delete Lock to Protect Azure Resource

## 🎯 Objective

Apply a **Delete Lock** to a Virtual Machine to prevent accidental deletion.

---

## 📌 Overview

Azure Resource Locks provide protection for critical resources.  

## 🛠️ Steps Performed

### Step 1: Create a Test Virtual Machine
- Navigate to Azure Portal
- Click **Create Resource**
- Select **Virtual Machine**
- Choose:
  - Subscription
  - Resource Group
  - Region: Central India
- Complete deployment

---

### Step 2: Apply Delete Lock

- Open the created Virtual Machine
- In the left menu → Click **Locks**
- Click **Add**
- Configure:
  - Lock Name → DeleteProtection
  - Lock Type → Delete
- Click **OK**

---

## 🔍 Testing the Lock

### ❌ Attempt to Delete VM

- Click **Delete** on the Virtual Machine
- Confirm deletion

Result:
Deletion failed.

Error:
The resource is locked and cannot be deleted.

---

### ✅ Attempt to Modify VM

- Restart the Virtual Machine
- Resize the Virtual Machine

Result:
Modification was allowed.

(Delete Lock only prevents deletion, not modification.)

---

## 📊 Outcome

- Virtual Machine deletion was successfully blocked.
- Resource modifications were allowed.
- Delete Lock protection validated.

---


