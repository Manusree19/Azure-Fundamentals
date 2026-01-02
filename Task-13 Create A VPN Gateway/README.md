# 🔐 Task 14 – Azure VPN Gateway (From Scratch)

## 🎯 Objective
To design and deploy a **secure hybrid networking setup** by configuring an **Azure VPN Gateway** that connects an **Azure Virtual Network (VNet)** with an **on-premises network** using an **IPsec Site-to-Site (S2S) VPN**.

---

## 🏗️ Architecture Overview
On-premises network  
⬇️  
**Encrypted IPsec VPN Tunnel**  
⬇️  
Azure VPN Gateway  
⬇️  
Azure Virtual Network (VNet & Subnets)

---

## 🧱 Resources Created
- Resource Group  
- Virtual Network (VNet)  
- Application Subnet  
- Gateway Subnet  
- Azure VPN Gateway  
- Public IP Address  
- Local Network Gateway  
- Site-to-Site VPN Connection  

---

## 📝 Steps 

### 🔹 Step 1: Create Resource Group
- Name: `rg-vpn-lab`  
- Region: Central India  

---

### 🔹 Step 2: Create Virtual Network
- Name: `vnet-vpn-lab`  
- Address space: `10.0.0.0/16`  
- Subnet:
  - Name: `app-subnet`
  - Range: `10.0.1.0/24`

---

### 🔹 Step 3: Create Gateway Subnet
- Subnet name: `GatewaySubnet` *(mandatory)*  
- Address range: `10.0.255.0/27`

> VPN Gateway cannot be deployed without a Gateway Subnet.

---

### 🔹 Step 4: Create Azure VPN Gateway
- Name: `vpn-gateway-lab`  
- Gateway type: VPN  
- VPN type: Route-based  
- SKU: `VpnGw1`  
- Virtual Network: `vnet-vpn-lab`  
- Public IP: `vpn-gateway-ip`  

---

### 🔹 Step 5: Create Local Network Gateway
Represents the on-premises network in Azure.

- Name: `lng-onprem`  
- Public IP (demo): `203.0.113.10`  
- Address space: `192.168.1.0/24`

---

### 🔹 Step 6: Create Site-to-Site VPN Connection
- Connection name: `s2s-connection`  
- Connection type: Site-to-Site  
- Shared Key (PSK): `Azure@123`  

---

## 🔎 Verification & Status

### ✅ VPN Gateway Verification
- **Provisioning state:** `Succeeded`  
- Public IP successfully assigned  
- Gateway Subnet present  

> Azure VPN Gateway does not show a “Running” status like VMs.  
> A **Succeeded provisioning state** confirms successful deployment.

---

---
