# azure-secure-webapp
# Azure Secure Web Application 🚀

## 📌 Overview
This project demonstrates deploying a secure web application on Azure using best practices for networking, security, and identity management.

---

## 🏗️ Architecture
- Azure Virtual Machine (Linux)
- Azure Virtual Network (VNet) & Subnet
- Network Security Group (NSG)
- Azure Key Vault
- Managed Identity (RBAC)
- Nginx Web Server

---

## ⚙️ Implementation Steps

### 1. Infrastructure Setup
- Created Resource Group
- Configured VNet and Subnet
- Created NSG with inbound rules (SSH, HTTP)

### 2. Virtual Machine
- Deployed Ubuntu VM
- Configured secure access
- Installed Nginx

### 3. Web Hosting
- Hosted Nginx website
- Verified public access via IP

### 4. Security Implementation 🔐
- Created Azure Key Vault
- Stored secrets securely
- Enabled Managed Identity on VM
- Assigned RBAC role (Key Vault Secrets User)

### 5. Secret Access
- Accessed Key Vault secrets from VM using Azure CLI
- Eliminated need for hardcoded credentials

---

## 🔐 Key Learning
Using Managed Identity with Azure Key Vault ensures secure, credential-free access to secrets, aligning with Zero Trust security principles.

---

## 📸 Screenshots
(Add your screenshots here)

---

## 🚀 Outcome
- Secure cloud architecture implemented
- End-to-end deployment completed
- Real-world Azure architecture experience

---

## 🔗 Author
Shruthi Chennaveni
