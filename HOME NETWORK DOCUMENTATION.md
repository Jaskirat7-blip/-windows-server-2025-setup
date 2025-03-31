# Home Network Overview

This document provides a comprehensive breakdown of my home network, covering both physical and logical topology along with some essential configurations. It present a clear understanding of how everything is connected, how theymcommunicate, and how the network is secured.

## 1. **Physical Topology of My Home Network**

The physical topology maps out the actual setup of all the hardware devices in my home network and how they are physically connected. 

- **Router**: Positioned in the living room, it serves as the central hub of the network and connects directly to the modem via an Ethernet cable (eth0).
- **Switch**: Located in the home office, this switch is connected to the router by another Ethernet cable (eth1), providing additional wired connections.
- **Access Points**: Placed in various rooms (bedrooms, living room, office), they provide Wi-Fi coverage to the entire house. Each is connected to the switch using Ethernet cables (eth2, eth3, eth4).
- **Computers and Devices**:
    - **Desktop PC**: Connected to the switch with a wired Ethernet connection (eth5).
    - **Laptop**: Wirelessly connected to the router via Wi-Fi (wlan0).
    - **Printer**: Also connected wirelessly to the router via Wi-Fi (wlan1).
      
### Physical Network Diagram
![image](https://github.com/user-attachments/assets/0af15cff-b461-4bcf-a8ac-b76070e09fa1)

## 2. **Logical Topology of the Network**

The logical topology illustrates how the devices communicate and how the network is segmented, including IP addressing and routing.

- **IP Addressing**:
    - **Router**: 192.168.16.1
    - **Desktop PC**: 192.168.16.2
    - **Laptop**: 192.168.16.4
    - **Printer**: 192.168.16.3
    - **Access Points**: 192.168.16.7

- **Subnets**:
    - **Default Gateway**: 192.168.16.1/24
    - **DHCP Range**: 192.168.16.100-192.168.16.200
- **Network Segmentation**:
    - VLAN 10:Main Network which includes all the devices of the house.
      
### Logical Network Diagram
![image](https://github.com/user-attachments/assets/d7dfc56c-d4a9-47a4-aa55-ec1719232672)

## 3. **Network Addressing Documentation**

Here is a table showing the assigned IP addresses and other details for the devices on my network:

| Device         | IP Address     | Description           |
|----------------|----------------|-----------------------|
| Router         | 192.168.16.1   | Main Router           |
| Desktop PC     | 192.168.16.2   | Wired Desktop         |
| Laptop         | 192.168.16.4   | Wireless Laptop       |
| Printer        | 192.168.16.3   | Wireless Smart TV     |
| Access Point   | 192.168.16.7   | Bedroom Access Point  | 

## 4. **Device Information**

This section provides further details on the primary devices that form the backbone of my home network:

| Device         | Brand          | Model            |
|----------------|----------------|------------------|
| **Router**     | ASUS           | RT-AC68U         |
| **Switch**     | TP-Link        | TL-SG108         |
| **Access Point** | TP-Link    | AC750            |

## 6. **Securing Login Credentials**

To ensure the security of my sensitive data, all login credentials, including router admin passwords and device logins, are stored in a reliable password manager. This password manager is protected by a master password, which I keep securely offline in an encrypted location. For added security, I enable two-factor authentication (2FA) on all accounts that support it, providing an extra layer of protection against unauthorized access.


## 7. **Summary and Conclusion**

This document provides a thorough overview of the physical and logical structure of my home network. It includes detailed information on network addressing, device configurations, and the security measures in place to keep the network running smoothly. By following the guidelines presented here, I am able to easily troubleshoot any issues and make updates or improvements to my network as needed, ensuring its efficiency and safety.








