# Task-22: Add Discovery Tool in Azure Migrate

## Objective
Enable Azure Migrate discovery tool by creating and registering an Azure Migrate appliance to discover and assess servers for migration.

---

## Prerequisites
- Azure Free Tier account
- Azure Migrate Project created (Task-21 completed)
- Access to Azure Portal

---

## Steps

1. Sign in to Azure Portal  
   https://portal.azure.com

2. Search for:
   `Azure Migrate`

3. Click on your Azure Migrate project  
   Example:
   `Azure-Migrate-Project`

4. In the Azure Migrate dashboard, go to:

   Migration goals → Servers → Azure Migrate: Discovery and assessment

5. Click on:
   `Discover`

---

6. Configure discovery settings:

   Replication type:
   `Using agentless replication`

   Appliance type:
   `Add a new Azure Migrate appliance`

---

7. Generate project key:

   Enter appliance name:

Click:
`Generate key`

---

8. Verify deployment

After successful deployment, you will see:

- Project key generated
- Appliance registered successfully
- Deployment status: Succeeded

---

## Output

Azure Migrate appliance successfully created and discovery tool enabled.

---

