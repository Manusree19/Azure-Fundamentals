# Task 32 – Restrict Resource Creation to One Region Using Azure Policy

## 🎯 Objective
Restrict resource creation to **Central India** region using Azure Policy.

---

## 📌 Overview

This task demonstrates how to enforce location restrictions at the **subscription level** using a built-in Azure Policy called **Allowed locations**.

---

## 🛠️ Steps Performed

### Step 1: Navigate to Azure Policy
- Login to Azure Portal
- Search for **Policy**
- Click on **Definitions**

---

### Step 2: Select Built-in Policy
- Search for: `Allowed locations`
- Select the built-in policy: **Allowed locations**

---

### Step 3: Assign the Policy
- Click **Assign**
- Select **Scope** → Choose the target **Subscription**
- Under Parameters → Select only:
  - ✅ Central India
- Click **Review + Create**
- Click **Create**

---

## 🔍 Testing the Policy

### Test Case 1: Non-Allowed Region
- Attempted to create a Virtual Machine in **East US**
- Result: ❌ Deployment failed
- Error: *Request disallowed by policy*

---

### Test Case 2: Allowed Region
- Attempted to create a Virtual Machine in **Central India**
- Result: ✅ Deployment succeeded

---

## 📊 Outcome

- Policy successfully restricted resource creation to Central India.
- Subscription-level governance enforced.
- Non-compliant deployments were automatically denied.

---


