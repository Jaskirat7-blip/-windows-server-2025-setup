# Standard Operating Procedure (SOP)

**Company Name:** MITT
**Company Address:** 130 Henlow Bay,Winnipeg,Manitoba
**Company Phone Number:** 431XXXXXXX  
**Version:** 1.0  
**Written by:** Jaskirat Brar
**Approved by:** Filex
**Date:** 03-26-2025
## Purpose

This SOP highlights the steps for preparing a Windows Server 2025 environment. This involves installation,configuration and network setup to make sure the system is ready to use.
## Application

This SOP applies to IT system administrators responsible for setting up and maintaining Windows Server 2025.
## Definitions

- **DNS :** Domain Name System which translates domain names to IP addresses
- **DHCP :** Dynamic Host Configuration Protocol assigns IP addresses to a device on network.
- **Active Directory (AD):** Used to manage permissions.
- ## Procedure Steps

### Step 1: Requirements for system
**Hardware Requirements:**
   - Minimum CPU: 1.4 Ghz
   - RAM: 4 GB minimum 
   - Storage: 80 GB 
   - Network Adapter: At least one network card.
   - 
2. **Software Requirements:**
   - Windows Server 2025 installation media (USB/DVD).
     
### Step 2: Install Windows Server 2025


   - Insert the installation USB or DVD into the server.
   - Power on the server and press the key to access the boot menu.
   - Select the USB/DVD drive and boot the system.
   - Select the language,time and keypord settings.
   - Click **Install Now**.
   - When prompted select the Custom Intsallation option,and select the disk where to install the OS.
   - Complete the installation and let the server restart.
  
  ### Step 3: Initial Configuration

1.  **Set Hostname:**
   - Go to **Server Manager**.
   - Navigate to **Local Server**, and change the computer name to a proper hostname.

2. **Set Administrator Password:**
   - During installation, make sure to give a strong password for administrator.

3. **Time Zone and Date Configuration:**
     - Go to **Control Panel > Date and Time** and configure it to match your region.
       
  ### Step 4: Network Configuration

1. **Assign Static IP:**
   - Go to settings>Network&Internet>Ethernet
   - Go to change adapter settings.
   - Assign a static IP address.

  ## Step 5: Install Roles and Features

 **Install Active Directory Role:**
   - Go to **Server Manager** > **Add Roles and Features**.
   - Install- Active Directory Domain Services
            - DNS Server
            - DHCP Server
            - File and Storage Services
            - Windows Backup
### Step 6: Update The Server
     - Go to settings>Update&Security>Windows Update
     - Select Check for updates
     - Install the latest version.
     
  ### Resources

- [Windows Server 2025 Installation Guide](https://www.microsoft.com/en-us/)
- [Microsoft Documentation]_(https://learn.microsoft.com)
- [GitHub Repositories for Server Configuration Scripts](https://github.com/)


  
