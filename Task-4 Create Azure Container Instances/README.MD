## Task 04 – Create Azure Container Instance (ACI)

🎯 **Objective**  
Deploy a containerized application using **Azure Container Instances (ACI)** without managing Virtual Machines or Kubernetes.

---

📝 **Steps**

### 1️⃣ Navigate to Azure Portal
- Sign in to **Azure Portal**
- Click **Create a resource**
- Search for **Container Instances**
- Click **Create**

---

### 2️⃣ Basics Tab
- **Subscription**: Select your active subscription  
- **Resource Group**: Choose existing RG or create a new one  
- **Container name**: `container  
- **Region**: Select a nearby region (e.g., Central India)  
- **Availability zones**: None  

---

### 3️⃣ Image Source
- **Image source**: Quickstart images  
- **Image**: `nginx` (or Hello World Linux)  
- **OS type**: Linux  

---

### 4️⃣ Size Configuration
- **CPU**: 1 vCPU  
- **Memory**: 1.5 GB  

---

### 5️⃣ Networking Tab
- **IP address type**: Public  
- **DNS name label**: containerdemo
- **Ports**:  
  - Port: `80`  
  - Protocol: `TCP`  

---

### 6️⃣ Advanced Tab
- Leave all settings as default  

---

### 7️⃣ Review + Create
- Validate configuration  
- Click **Create**  
- Wait for deployment to complete  

---

✅ **Verification**
- Go to **Container Instances → aci-task04 → Overview**
- Copy the **Public IP address**
- Open browser → `http://<Public-IP>`
- Confirm the containerized app is running


