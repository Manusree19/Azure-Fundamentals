# ✅ Task 07 – Create Deployment Slots in Azure App Service

## 🎯 Objective
To create and use **Deployment Slots** in **Azure App Service** to understand **zero-downtime deployments** and safe application updates using slot swapping.

---
## 📝 Prerequisites
- Existing Azure App Service
- App Service Plan: **Standard (S1) or higher**
- Azure Portal access

> ⚠️ Note: Deployment Slots are **not available** in Free (F1) or Basic (B1) plans.

---

## 🧩 Steps Performed

### 1️⃣ Open Azure App Service
- Logged in to **https://portal.azure.com**
- Navigated to **App Services**
- Selected the existing App Service

---

### 2️⃣ Create a Deployment Slot
- Clicked **Deployment slots**
- Selected **+ Add Slot**
- Slot Name: `staging`
- Cloned settings from: `production`
- Clicked **Add**

---

### 3️⃣ Verify Deployment Slots
- Confirmed two slots are running:
  - **Production** (100% traffic)
  - **Staging** (0% traffic)
- Verified each slot has a unique URL

---

### 4️⃣ Swap Deployment Slots
- Clicked **Swap**
- Source: `staging`
- Target: `production`
- Completed swap successfully
  
## ✅ Verification
- Confirmed both slots are in **Running** state
- Verified production URL after swap
- Ensured no downtime during deployment

---

