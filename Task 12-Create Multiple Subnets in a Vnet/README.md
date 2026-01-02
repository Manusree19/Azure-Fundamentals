# ✅ Task 12 – Create Multiple Subnets in an Azure Virtual Network

## 🎯 Objective
To create **multiple subnets** within a single **Azure Virtual Network (VNet)** to logically separate workloads and improve **network security, organization, and scalability**.

---

## 🪜 Steps 

### 🔹 Step 1: Sign in to Azure Portal
- Open https://portal.azure.com
- Sign in with your Azure account

---

### 🔹 Step 2: Open Virtual Network
1. Navigate to **Virtual Networks**
2. Select your existing Virtual Network  
 
### 🔹 Step 3: Open Subnets
- In the left menu, click **Subnets**
- Click **+ Subnet**

---

### 🔹 Step 4: Create Frontend Subnet
Enter the following details:
Subnet name: backend-subnet
Address range: 10.0.2.0/24
- Leave all other options as default
- Click **Save**
✅ Frontend subnet created successfully

---
### 🔹 Step 5: Create Backend Subnet
1. Click **+ Subnet** again
2. Enter the following details:
3. Subnet name: backend-subnet
   Address range: 10.0.2.0/24
- Ensure the address range does **not overlap** with other subnets
- Click **Save**
✅ Backend subnet created successfully
---
## ✅ Verification
- Both subnets are listed under the Virtual Network
- Address ranges are unique and non-overlapping





