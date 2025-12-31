# Task 03 – Create Virtual Machine Scale Set (vmss1)

## 🎯 Objective
Deploy an Azure Virtual Machine Scale Set named **vmss1** to automatically manage and scale multiple identical virtual machines for high availability.

---

## 📝 Steps

### 1️⃣ Navigate to Azure Portal
- Sign in to the Azure Portal
- Go to **Virtual Machine Scale Sets**
- Click **Create → Azure Virtual Machine Scale Set**

---

### 2️⃣ Basics Tab
- **Subscription:** Select your active subscription  
- **Resource Group:** Choose your existing lab Resource Group  
- **Virtual Machine Scale Set Name:** `vmss1`  
- **Region:** Central India (or nearest region)  
- **Orchestration Mode:** Uniform  
- **Image:** Ubuntu Server 20.04 LTS (or Windows Server 2022)  
- **VM Size:** Standard_B2s (or any available size)  
- **Authentication Type:** Password  
- **Username:** azure user 
- **Password:** Set a strong password  
- **Instance Count:** 2  

---

### 3️⃣ Scaling Tab
- **Scaling Mode:** Autoscaling  
- **Minimum Instances:** 2  
- **Maximum Instances:** 5  
- **Scale-out Rule:** CPU > 75%  
- **Scale-in Rule:** CPU < 30%  

---

### 4️⃣ Networking Tab
- **Virtual Network:** Existing VNet or create new  
- **Subnet:** Default  
- **Load Balancer:** Create new  
- **Public IP:** Enabled  
- **Inbound Ports:**  
  - SSH (22) for Linux  
  - RDP (3389) for Windows  

---

### 5️⃣ Management, Monitoring, Advanced, Tags
- Leave all settings as default

---

### 6️⃣ Review + Create
- Review configuration
- Click **Create**
- Wait for deployment to complete

---

## ✅ Verification
- Go to **Virtual Machine Scale Sets**
- Select **vmss1**
- Verify:
  - Provisioning state is **Succeeded**
  - Instance count is correct
  - Load balancer is attached

---
