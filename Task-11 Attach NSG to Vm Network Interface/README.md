# ✅ Task 11 – Attach Network Security Group (NSG) to VM Network Interface (NIC)

## 🎯 Objective
To attach a **Network Security Group (NSG)** directly to a **Virtual Machine’s Network Interface (NIC)** in order to apply security rules at the VM level for more granular control.

---

## 📝 Prerequisites
- An existing **Virtual Machine**
- An existing **Network Security Group (NSG)** with inbound rules
- VM should be in **running state**

---

## 🪜 Steps 

### 1️⃣ Login to Azure Portal
- Go to https://portal.azure.com
- Sign in with your Azure account

---

### 2️⃣ Open Virtual Machine
- Search for **Virtual Machines**
- Select your VM  
  Example: `windows-vm-01`

---

### 3️⃣ Open Networking Settings
- In the left menu, click **Networking**
- Under **Network Interface**, click the **NIC name**

---

### 4️⃣ Attach NSG to NIC
- In the NIC page, click **Network security group**
- Click **Associate**
- Select existing NSG  
  Example: `nsg-demo`
- Click **Save**

---

### 5️⃣ Wait for Deployment
- Wait until the save operation completes successfully
- NSG is now attached to the VM NIC

---

## ✅ Verification
- Open the VM → Networking
- Confirm the **Network Security Group** is attached
- View **Effective security rules** to see applied rules

---
