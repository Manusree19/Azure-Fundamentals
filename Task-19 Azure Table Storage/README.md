
## 🎯 Objective
Create an Azure Table Storage resource, insert entities, and verify data storage using cloud-based NoSQL key-value storage.
## 📝 Steps
### 🔹 Step 1 — Create Storage Account
1. Sign in to **Azure Portal**.
2. Click **Create a resource → Storage Account**.
3. Fill the details:
   - Subscription: Active subscription  
   - Resource Group: Existing resource group  
   - Storage Account Name: `tablelabstorage` (unique)  
   - Region: Central India  
   - Performance: Standard  
   - Redundancy: LRS  
4. Click **Review + Create → Create**.
---
### 🔹 Step 2 — Open Table Storage
1. Open the created **Storage Account**.
2. From the left menu, click **Storage Browser**.
3. Expand **Tables**.
4. Click **+ Add table**.
5. Enter table name: 6. Click **Create**.

---

### 🔹 Step 3 — Insert Entity (Student Record)
1. Open the table **students**.
2. Click **+ Add entity**.
3. Enter values:
- **PartitionKey:** IT  
- **RowKey:** 001  

4. Add properties:

| Property Name | Data Type | Example Value |
|----------------|------------|----------------|
| Name | String | Manu |
| Marks | Int32 | 65|
| Course | String | Azure|

5. Click **Insert**.

---

### 🔹 Step 4 — Verify Data
1. Refresh the table.
2. Confirm the student record appears in the grid.
3. Validate PartitionKey, RowKey, and property values.

---

## ✅ Verification Checklist
✔️ Storage account created successfully  
✔️ **students** table created  
✔️ Entity added with PartitionKey = IT and RowKey = 001  
✔️ Properties (Name, Marks, Course) stored successfully  
✔️ Data visible in Table Storage  

---
