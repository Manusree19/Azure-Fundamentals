# Task 40 – Create CPU Alert Rule for Virtual Machine

## 🎯 Objective

Create a metric-based alert that triggers when the Virtual Machine CPU usage exceeds 80%.

---

## 📌 Overview

Azure Monitor allows users to create alerts based on performance metrics.

In this task, a **Metric Alert** was configured to monitor the Percentage CPU of a Virtual Machine.

---

## 🛠️ Steps Performed

### Step 1: Navigate to Virtual Machine
- Login to Azure Portal
- Search for **Virtual Machines**
- Select the target VM

---

### Step 2: Create Alert Rule
- Go to **Monitoring** section
- Click **Alerts**
- Click **+ Create**
- Select **Alert rule**

---

### Step 3: Configure Condition
- Signal type → Metric
- Signal name → Percentage CPU
- Condition → Greater than
- Threshold value → 80
- Aggregation type → Average
- Evaluation period → 5 minutes

---

### Step 4: Configure Action Group
- Click **Create Action Group**
- Action Group Name → CPUAlertGroup
- Add action → Email notification
- Enter email address
- Save Action Group

---

### Step 5: Review and Create
- Provide Alert rule name → HighCPUAlert
- Click **Review + Create**
- Click **Create**

---

## 🔍 Observations

- Alert rule created successfully.
- System will monitor CPU continuously.
- Email notification will trigger if CPU > 80%.

---

## 📊 Outcome

- Successfully configured Metric Alert.
- Enabled proactive monitoring.
- Implemented automated notification system.

---

