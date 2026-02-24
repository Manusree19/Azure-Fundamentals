# Task 38 – Create Budget and Cost Alert in Azure

## 🎯 Objective

Create a monthly budget and configure an alert to monitor Azure spending.

---

## 📌 Overview

Azure Budgets allow organizations to:

- Set spending limits
- Receive alerts when thresholds are crossed
- Prevent unexpected high bills

In this task, a monthly budget was created with an 80% alert threshold.

---

## 🛠️ Steps Performed

### Step 1: Navigate to Budgets
- Login to Azure Portal
- Search for **Cost Management + Billing**
- Click **Cost Management**
- Select **Budgets** (under Monitoring section)

---

### Step 2: Create New Budget
- Click **+ Add**
- Configure the following:

  - Budget Name → MonthlyBudget  
  - Reset Period → Monthly  
  - Start Date → Current date  
  - Budget Amount → ₹2000 (example)

---

### Step 3: Configure Alert Threshold
- Alert Type → Actual Cost  
- Threshold → 80  
  (Note: Do not include % symbol. Enter numeric value only.)
- Add email recipient
- Click **Create**

---

## 🔍 Observations

- Budget created successfully.
- Alert will trigger when spending reaches 80% of ₹2000.
- Notification will be sent via email.

---

## 📊 Outcome

- Monthly budget successfully configured.
- Cost alert mechanism enabled.
- Budget monitoring feature validated.

---

## 🧠 Key Learnings

- Budgets help control Azure spending.
- Alerts notify users before exceeding limits.
- Threshold values must be numeric (without % symbol).
- Budget monitoring is critical in enterprise environments.

---

