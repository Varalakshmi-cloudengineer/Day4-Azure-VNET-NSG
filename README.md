# Day 4 - Azure Virtual Network and Network Security Group Project

This task demonstrates how to create a **Virtual Network (VNet)** in Microsoft Azure, set up a custom subnet, create a **Network Security Group (NSG)**, add inbound rules, and associate it with the subnet for secured traffic control.

---

## 🧱 Azure Resources Created

- **Resource Group:** vnet-rg  
- **Virtual Network:** myvnet01  
- **Subnet Name:** mysubnet01  
- **Network Security Group:** my-nsg  
- **Inbound Rule:** Allowed SSH (Port 22) or RDP (Port 3389)

---

## 🔐 What I Did

- Created a custom Virtual Network in Azure with a specific address range
- Created a subnet inside the VNet to host resources
- Created an NSG to control inbound traffic
- Added a rule to allow SSH (or RDP) connections
- Associated NSG with the subnet

---

## 📘 Learnings

- How to configure networking in Azure
- How to secure traffic using NSGs
- How to manage access rules for cloud-based VMs
- Subnet-level NSG application

---

## ✅ Cleanup

All resources were deleted after completion to avoid charges.

---

## 👩‍💻 Author

**Varalakshmi**  
Cloud Support Engineer | Azure & AWS Enthusiast  
GitHub: [Varalakshmi-cloudengineer](https://github.com/Varalakshmi-cloudengineer)
