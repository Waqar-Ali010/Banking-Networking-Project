# Banking-Networking-Project
# 🏦 Bank Network Topology (Cisco Packet Tracer)

This project demonstrates the design and configuration of a **bank enterprise network** using **Cisco Packet Tracer**.  
The network was designed with scalability, security, and efficiency in mind — implementing VLANs, DHCP, OSPF, SSH, Port Security, and Wireless connectivity for each department.


## 🧩 Project Overview
The bank network is divided into multiple departments, each assigned a unique VLAN and subnet.  
The design follows a **Hierarchical Network Model** to ensure scalability and structured communication between departments.

### Key Objectives
- Use **OSPF** as the routing protocol to advertise routes between departments.  
- Implement **Wireless Networks** for every department to support wireless users.  
- Each department (except the Server Room) supports around **60 users** (wired + wireless).  
- All **host devices** obtain IPv4 addresses **automatically** through DHCP.  
- Ensure **full inter-department communication** using Inter-VLAN Routing on Layer 3 switches.  
- Deploy **HTTP and E-mail servers** in the Server Room.  
- Assign **dedicated DHCP servers** in the Server Room for dynamic IP allocation.  
- Configure **SSH** on all routers for secure remote login.  
- Apply **basic configurations** on all devices:
  - Hostnames  
  - Console and enable passwords  
  - Banner messages  
  - Disable domain IP lookup  
  - Encrypt all passwords  
- Implement **Port Security** using sticky MAC addressing with violation mode set to *shutdown*.  
- Perform **Subnetting** using base network `192.168.10.0/24` for each VLAN based on user requirements.  
- Test and verify network communication to ensure all departments can connect seamlessly.


## ⚙️ Technologies Implemented
- Cisco Packet Tracer Network Design  
- Hierarchical Network Architecture  
- Correct Cabling of Networking Devices  
- VLAN Creation and Port Assignments  
- Subnetting and IP Address Planning  
- Inter-VLAN Routing (SVI Configuration on L3 Switches)  
- Dedicated DHCP Server Configuration  
- SSH for Secure Remote Access  
- OSPF Routing Protocol Configuration  
- Port-Security with Sticky MAC and Violation Shutdown  
- Wireless LAN (WLAN) Configuration using Access Points  
- HTTP and E-mail Server Configuration  
- End Device Configuration and Connectivity Testing  

## 🧠 Network Planning and Addressing
- **Base Network:** 192.168.10.0/24  
- **Subnetting:** Calculated according to departmental host requirements (approx. 60 users per VLAN).  
- **Each VLAN:** Separate Subnet, VLAN ID, and IP Address Range  
- **Server Room:** Dedicated DHCP, HTTP, and E-mail Servers


## 🧪 Testing and Verification
✅ Verify DHCP assignment for all hosts  
✅ Confirm OSPF routing tables between routers  
✅ Test SSH access from remote PCs to routers  
✅ Ping across VLANs to confirm inter-department communication  
✅ Verify Port-Security functionality and sticky MAC behavior  
✅ Confirm wireless and wired device connectivity  


## 🖥️ Tools Used
- Cisco Packet Tracer  
- Cisco IOS Commands  
- Windows/Linux End Devices (for testing)  








