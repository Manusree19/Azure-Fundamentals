# ✅ Task 09 – Create Network Security Group (NSG)

## 🎯 Objective
To create a **Network Security Group (NSG)** and configure inbound and outbound rules to control network traffic in Azure.

---

## 📝 Steps 
### 1️⃣ Login to Azure Portal
- Logged in to https://portal.azure.com
- Clicked **Create a resource**
- Searched for **Network Security Group**
- Clicked **Create**

---

### 2️⃣ Basics Tab
- **Subscription**: Active subscription
- **Resource Group**: Existing resource group
- **NSG Name**: `nsg-demo`
- **Region**: Same region as Virtual Network

---

### 3️⃣ Create NSG
- Clicked **Review + Create**
- Deployment completed successfully

---

### 4️⃣ Add Inbound Security Rules
- Allowed **HTTP (Port 80)**
- Allowed **HTTPS (Port 443)**
- Allowed **RDP (Port 3389)** or **SSH (Port 22)**
- Default rule: Deny all other traffic

---

## ✅ Verification
- NSG status shows **Succeeded**
- Inbound rules are visible and active

---
