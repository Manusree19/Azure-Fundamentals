# ✅ Task 20 — Configure Blob Lifecycle Management (Azure)

## 🎯 Objective
Automatically move and delete blobs based on age using Azure Lifecycle Management rules to optimize storage cost and enforce data retention policies.

##  Steps

### 🔹 Step 1 — Open Storage Account
1. Sign in to Azure Portal  
2. Search for **Storage accounts**  
3. Open your storage account  

---

### 🔹 Step 2 — Navigate to Lifecycle Management
1. In the left menu, go to:  
   **Data management → Lifecycle management**  
2. Click **+ Add rule**

---

### 🔹 Step 3 — Configure Rule Basics

| Setting | Value |
|--------|--------|
| Rule name | move-to-cool-delete |
| Rule scope | Apply rule to all blobs |
| Blob type | Block blobs |
| Prefix filter | Leave empty |

Click **Next**

---

### 🔹 Step 4 — Configure Base Blob Actions

Enable the following actions:

- ✅ Move to cool storage after **30 days**
- ✅ Move to archive storage after **60 days**
- ✅ Delete blob after **120 days**

Click **Next → Add**

---

### 🔹 Step 5 — Save Rule
1. Review the rule summary  
2. Click **Save**  

The lifecycle rule becomes active automatically.

---

## ✅ Verification
- Open **Lifecycle management**
- Confirm rule status is **Enabled**
- Verify tier transitions:
  - Hot → Cool → Archive → Delete

