# Task 05 – Create Azure Function

## 🎯 Objective
Create and deploy an Azure Function using the Azure Portal to understand serverless computing and event-driven architecture without managing servers.

---

## 📝 Steps 

### 1️⃣ Navigate to Azure Portal
- Sign in to https://portal.azure.com
- Click **Create a resource**
- Search for **Function App**
- Click **Create**

---

### 2️⃣ Basics Tab
- **Subscription:** Select your active subscription  
- **Resource Group:** Choose existing RG or create a new one  
- **Function App name:** `task05-function-app` (must be unique)  
- **Publish:** Code  
- **Runtime stack:** Python  
- **Version:** 3.10  
- **Region:** Central India (or nearest region)  
- **Operating System:** Linux  
- **Plan type:** Consumption (Serverless)

---

### 3️⃣ Storage
- **Storage account:** Create new (default settings)

---

### 4️⃣ Monitoring
- **Application Insights:** Enable (recommended for monitoring)

---

### 5️⃣ Review + Create
- Validate all configurations
- Click **Create**
- Wait for deployment to complete

---

## ⚙️ Create a Function

1. Go to **Function App → task05-function-app**
2. Click **Functions → Create**
3. Choose **HTTP trigger**
4. Authorization level: **Anonymous**
5. Click **Create**

---

## ✅ Verification
- Open the created function
- Click **Get Function URL**
- Paste URL in browser
- Confirm the function is running successfully

Azure • AzureFunctions • Serverless • CloudComputing • AzureFundamentals • LearningInPublic
