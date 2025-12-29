# Task 02 – Create Windows Virtual Machine in Azure

## 🎯 Objective
Deploy a Windows Virtual Machine in Microsoft Azure named **windows-vm-01** inside the existing resource group **rg-windows-vm**.

---

## 📝 Steps

### 1️⃣ Navigate to Azure Portal
- Sign in to the Azure Portal  
- Go to **Virtual Machines → Create → Azure virtual machine**

---

### 2️⃣ Basics Tab
- **Subscription:** Azure subscription 1  
- **Resource Group:** rg-windows-vm  
- **Virtual Machine Name:** windows-vm-01  
- **Region:** Central India  
- **Image:** Windows Server 2025 Datacenter  
- **Size:** Standard_B2s (2 vCPU, 4 GB RAM)  
- **Authentication Type:** Password  
- **Username:** azure user
- **Password:** Strong password (configured during creation)  

---

### 3️⃣ Disks Tab
- **OS Disk Type:** Standard SSD (Default)  
- **Data Disks:** None  

---

### 4️⃣ Networking Tab
- **Virtual Network:** Auto-created by Azure  
- **Subnet:** Default  
- **Public IP:** Enabled  
- **NIC Network Security Group:** Basic  
- **Inbound Port Rule:** Allow RDP (3389)  

---

### 5️⃣ Management, Monitoring, Advanced, Tags
- All settings left as default  

---

### 6️⃣ Review + Create
- Validated all configurations  
- Clicked **Create**  
- Deployment completed successfully  

---

## ✅ Verification
- Navigated to **Virtual Machines → windows-vm-01 → Overview**
- Verified:
  - Deployment status: **Succeeded**
  - VM state: **Running**
  - Public IP assigned

---

#
