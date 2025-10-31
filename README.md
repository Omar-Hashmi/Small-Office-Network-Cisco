---

# 🖧 Small Office Network Simulation (Cisco Packet Tracer)

## 📌 Overview
This project simulates a **Small Office Network** using Cisco Packet Tracer. It connects multiple departments within an organization through routing, switching, and static IP addressing. Each department operates within its own subnet, with dedicated routers, switches, and shared resources like printers and servers — reflecting a realistic office infrastructure.

---

## 🏢 Departments & Subnets

### 🔹 Computer Department
- **Subnet**: `192.168.3.0/24`
- **Devices**: 3 Employee PCs, 1 Manager PC, 1 Printer, 1 Switch
- **Gateway**: `192.168.3.1`

### 🔹 IT Department
- **Subnet**: `192.168.2.0/24`
- **Devices**: 2 Employee PCs, 1 Manager PC, 1 Printer, 1 Switch
- **Gateway**: `192.168.2.1`

### 🔹 Chairman Department
- **Subnet**: `192.168.1.0/24`
- **Devices**: 1 Chairman PC, 1 Vice Chairman PC, 1 Switch
- **Gateway**: `192.168.1.1`

### 🔹 Server Room
- **Subnet**: `1.0.0.0/24`
- **Devices**: 1 Server, 1 Maintenance Laptop, 1 Switch
- **Gateway**: `1.0.0.1`

---

## 🌐 Network Topology

- **Routers Used**:
  - Main Router: `10.0.0.1`
  - Secondary Router: `10.0.0.2`
- Each department connects via a dedicated switch
- Static IP addressing ensures stability and manageability
- Inter-department communication is enabled through static routing

---

## 📊 IP Addressing Scheme

| Department           | Network/Subnet   | Gateway IP     | Example Host IPs             |
|----------------------|------------------|----------------|------------------------------|
| Computer Department  | 192.168.3.0/24   | 192.168.3.1    | 192.168.3.2 – 192.168.3.6    |
| IT Department        | 192.168.2.0/24   | 192.168.2.1    | 192.168.2.2 – 192.168.2.5    |
| Chairman Department  | 192.168.1.0/24   | 192.168.1.1    | 192.168.1.2 – 192.168.1.3    |
| Server Room          | 1.0.0.0/24       | 1.0.0.1        | 1.0.0.2 – 1.0.0.3            |
| Router Interlink     | 10.0.0.0/30      | 10.0.0.1–2     | Router-to-Router connection  |

---

## 🧰 Tools & Technologies

- Cisco Packet Tracer
- Cisco Routers & Switches
- Static Routing Configuration
- IP Addressing & Subnetting
- LAN Connectivity

---

## ✨ Features

- ✅ Department-wise subnetting
- ✅ Static routing for inter-department communication
- ✅ Shared printers in Computer & IT departments
- ✅ Centralized server access across all departments
- ✅ Hierarchical topology with routers, switches, and hosts

---

## 🚀 How to Use

1. Open the `.pkt` file in Cisco Packet Tracer
2. Power on all devices and verify connections
3. Use the `ping` command to test connectivity:
   ```bash
   ping 192.168.1.2
   ping 1.0.0.2
   ```
4. Explore routing tables and confirm inter-department communication

---

## 🔧 Future Enhancements

- Implement DHCP for dynamic IP allocation
- Add firewall or ACLs for access control
- Configure DNS and Web Server in the Server Room
- Introduce VLANs for traffic segmentation

---

## 🗺️ Network Diagram

A visual representation of the complete network topology:

![Network Topology](https://github.com/user-attachments/assets/0b317b02-1cd6-420e-a4a4-2803ba04d3b5)

---

## 👨‍💻 Author

**Omar Hashmi**  
Network Design | Cisco Packet Tracer | Routing & Switching  
📍 Pakistan | 🎓 SZABIST 

---
