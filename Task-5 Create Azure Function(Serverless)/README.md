🚀 Task 05 – Create Azure Function (Serverless)
🎯 Objective

Create and test an Azure Function to understand serverless, event-driven computing without managing virtual machines or infrastructure.

📝 Steps
1️⃣ Navigate to Azure Portal

Sign in to Azure Portal

Click Create a resource

Search for Function App

Click Create

2️⃣ Basics Tab

Subscription: Select your active subscription

Resource Group: Choose existing RG or create a new one

Function App name: function-task05 (must be unique)

Publish: Code

Runtime stack: Python

Version: Latest available

Region: Select a nearby region (e.g., Central India)

Operating System: Linux

Plan type: Consumption (Serverless)

3️⃣ Storage Tab

Storage account: Create new

Leave all other settings as default

4️⃣ Monitoring Tab

Application Insights: No (for practice / learning)

5️⃣ Review + Create

Validate the configuration

Click Create

Wait for deployment to complete

6️⃣ Create Azure Function

Open the created Function App

Click Functions → + Create

Select Develop in portal

Choose HTTP trigger

Function name: HttpTriggerDemo

Authorization level: Function

Click Create

✅ Verification

Go to Function App → Functions → HttpTriggerDemo

Click Code + Test

Click Test/Run

Verify Status: 200 OK

Copy the Function URL

Open it in a browser to confirm successful execution
