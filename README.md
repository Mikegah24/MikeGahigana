#  Active Directory Lab on Azure

This project sets up a simple but realistic Active Directory lab using two Azure VMs:
- **DC1** – Windows Server 2022, configured as Domain Controller and DNS server
- **Client1** – Windows 10/11 Pro, joined to the domain

##  Objective
To simulate and understand Active Directory, DNS, domain join, user authentication, GPOs, and PowerShell scripting.

##  Lab Highlights
- Domain: `tech.lab`
- Active Directory + DNS setup
- Users created via PowerShell


##  Machines
- **DC1**: Static IP, AD DS, DNS
- **Client1**: Domain-joined, DNS set to DC1

##  Folder Structure
- `scripts/` - PowerShell scripts for automation
- `screenshots/` - Key setup and verification screenshots
- `network-diagram.png` - High-level architecture
- `setup-notes.md` - Detailed build and config steps

##  Scenarios
1. **GPO enforcement on domain user login**
2. **PowerShell-based user creation**

## 📸 Screenshots
See `screenshots/` folder.

## 🤝 What I Learned
- Networking basics in Azure (VNet, DNS, NSGs)
- Domain Controller setup
- Domain-joining Windows clients
- GPO creation and testing
- Using PowerShell for AD tasks
