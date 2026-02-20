# Task 33 – Enforce Mandatory Tag Using Azure Policy

## 🎯 Objective

Enforce a mandatory tag on all resources within a specific Resource Group.

Tag Requirement:

Environment = Production

---

## 📌 Overview

This task demonstrates how to use a built-in Azure Policy to enforce tagging standards on resources.

Tagging is commonly used in enterprises for:

- Cost tracking
- Environment identification
- Governance
- Resource organization

---

## 🛠️ Steps Performed

### Step 1: Navigate to Azure Policy
- Login to Azure Portal
- Search for **Policy**
- Click on **Definitions**

---

### Step 2: Select Built-in Policy

Search for:

Require a tag and its value on resources

Select:

**Require a tag and its value on resources**

Policy Details:
- Type: Built-in
- Category: Tags
- Effect: Deny

---

### Step 3: Assign the Policy

- Click **Assign**
- Scope → Select specific **Resource Group**
- Click **Select**

---

### Step 4: Configure Parameters

Set the following:

Tag Name → Environment  
Tag Value → Production  

Click **Review + Create**
Click **Create**

---

## 🔍 Testing the Policy

### ❌ Test Case 1 – Without Tag

- Attempted to create a Storage Account
- Did NOT add required tag
- Deployment failed

Error:
RequestDisallowedByPolicy  
Policy: Require a tag and its value on resources

---

### ✅ Test Case 2 – With Correct Tag

- Created Storage Account again
- Added tag:

Environment = Production

- Deployment succeeded

---

## 📊 Outcome

- Resources without required tag were blocked.
- Policy enforcement worked at Resource Group level.
- Tag compliance successfully validated.

---



