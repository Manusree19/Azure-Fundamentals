
## 🎯 Objective
To create an Azure Queue Storage service, add messages, view (peek) messages, and dequeue messages to understand asynchronous messaging in Azure.
  
## 📝 Steps

### ✅ Step 1 — Create Storage Account
- Logged into Azure Portal.
- Created a new Storage Account with:
  - Performance: Standard  
  - Redundancy: LRS  
  - Region: Central India  

---

### ✅ Step 2 — Create Queue
- Opened the storage account.
- Navigated to **Data storage → Queues**.
- Created a queue named `orderqueue`.

---

### ✅ Step 3 — Add Message
- Opened the queue.
- Clicked **Add message**.
- Added sample message:

---

### ✅ Step 4 — Peek Message
- Selected the message from the list.
- Viewed message properties without deleting the message.
- Verified message body, insertion time, and dequeue count.

---

### ✅ Step 5 — Dequeue Message
- Clicked **Dequeue message** from the toolbar.
- Message was removed from the queue successfully.

---

## 🔍 Verification 
- Queue created successfully  
- Message added and visible  
- Message peeked successfully  
- Message dequeued and queue became empty  

---
