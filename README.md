# Home-lab-portfolio
My hands-on IT projects and home lab documentation 
# Home Lab Portfolio – Logan Leach

Welcome to my home lab project portfolio! I'm currently pursuing a degree in IT at WGU, and this repository showcases the hands-on work I've been doing to build practical experience in networking, virtualization, and remote access.

---

## 🔧 Projects

### 🖥️ Dell PowerEdge R610 Server #1 – TrueNAS
- Configured with **RAID 5**
- Hosts **TrueNAS** for storage and backup
- Used primarily for **photo storage** and future NAS testing

### 🖥️ Dell PowerEdge R610 Server #2 – Proxmox
- Clean installation of **Proxmox VE**
- Configured with **RAID 5**
- Hosts **Ubuntu Linux VMs**
- Used for lab environments and testing different tools

## 🖥️ Windows Server 2022 Deployment in Proxmox

This project shows how I set up and configured Windows Server 2022 in my home lab using Proxmox. I used this server to practice installing roles like Active Directory and DNS.

---

## 💻 VM Setup in Proxmox
- **OS**: Windows Server 2022 (Evaluation ISO)
- **CPU**: 2 Cores
- **RAM**: 4 GB
- **Disk**: 80 GB
- **Network**: Default bridged adapter

---

## 🔧 Installation Steps
1. **Upload the Windows Server ISO** to Proxmox
2. **Create a new VM** and mount the ISO
3. **Install Windows Server 2022** inside the VM
4. **Set a static IP** and rename the server (example: `homelabserver`)
5. **Turn on Remote Desktop** for easier access

---

## 🧱 Roles I Installed
- ✅ Active Directory Domain Services (AD DS)
- ✅ DNS Server
- ✅ DHCP Server *(optional in my setup)*


Install-WindowsFeature AD-Domain-Services, DNS -IncludeManagementTools

---

### 🔐 Twingate Deployment
- Installed and configured **Twingate** for Zero Trust Network Access (ZTNA)
- Runs in a **Docker container** on my **Windows 11 PC**
- Secure remote access to my home lab without opening ports

### 🖱️ RustDesk Remote Access
- Installed and configured **RustDesk** on my phone
- Used to access my PC remotely through Twingate's secure tunnel

---

## 📚 Goals
- Expand my IT skills with real-world home lab experience
- Document my learning and tools used
- Transition into a full-time IT role with hands-on knowledge in infrastructure, virtualization, and secure remote access

---

## 🔗 Connect with Me
- [LinkedIn](https://www.linkedin.com/in/logan-leach-249a85232) 
- [WGU Student Portfolio (coming soon)]()

