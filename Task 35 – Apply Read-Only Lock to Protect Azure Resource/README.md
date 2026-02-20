# Task 35 – Apply Read-Only Lock to Protect Azure Resource

## 🎯 Objective

Apply a **Read-Only Lock** to a Virtual Machine to prevent both modification and deletion.

---

## 📌 Overview

Azure Resource Locks provide an additional layer of protection for critical resources.

A **Read-Only Lock** ensures that:

- The resource cannot be modified
- The resource cannot be deleted
- The resource can only be viewed

This type of lock is typically used in production environments where strict governance is required.

---

## 🛠️ Steps Performed

### Step 1: Navigate to Virtual Machine
- Login to Azure Portal
- Open **Virtual Machines**
- Select the test Virtual Machine

---

### Step 2: Apply Read-Only Lock
- In the left menu → Click **Locks**
- Click **+ Add**
- Configure:
  - Lock Name → ReadOnlyProtection
  - Lock Type → Read-only
- Click **OK**

---

## 🔍 Testing the Lock

### ❌ Test Case 1 – Attempt to Restart VM

- Click **Restart**
- Operation failed

---

### ❌ Test Case 2 – Attempt to Resize VM

- Try changing VM size
- Operation failed

---

### ❌ Test Case 3 – Attempt to Delete VM

- Click **Delete**
- Operation failed

Error:
The resource is locked and cannot be modified or deleted.

---

## 📊 Outcome

- Modification attempts were blocked.
- Deletion attempts were blocked.
- Read-Only Lock protection successfully validated.

---

