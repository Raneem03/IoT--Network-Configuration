# IoT--Network-Configuration
# 🌐 IoE Network Lab (Internet of Everything Simulation)

## 📌 Project Overview
This project simulates an Internet of Everything (IoE) network using Cisco Packet Tracer.  
It demonstrates how different devices (routers, servers, cloud, and smart devices) communicate in a unified network environment.

The network includes:
- ISP Router (DHCP + DNS)
- Home Gateway (Wireless Access)
- IoE Server (Device Management)
- Cloud (Network Bridge)
- Smart Devices (IoT)
- End Users (Laptop, Mobile)

---

## 🏗️ Network Topology
The system is divided into three main layers:

### 1. ISP Layer
- Provides internet connectivity
- Handles DHCP (IP assignment)
- Provides DNS services

### 2. Core Network (Cloud + Switch)
- Connects ISP with IoE infrastructure
- Bridges Ethernet and Coaxial connections

### 3. Home / IoE Layer
- Wireless Home Gateway
- Smart IoT devices
- User devices (Laptop, Smartphone)

---

## ⚙️ Key Configurations

### 📡 ISP Router
- DHCP enabled
- IP addressing pool configured
- DNS server assigned

### 🏠 Home Gateway
- Wireless enabled (WPA2 security)
- DHCP client mode
- Provides WiFi connectivity

### ☁️ Cloud Device
- Ethernet to Coaxial mapping configured
- Acts as communication bridge

### 🖥️ IoE Server
- HTTP service enabled
- IoT management service active
- Admin access enabled

---

## 📱 IoT Devices Included
- Smart Door 🚪
- Smart Light 💡
- Smart Fan 🌬️
- Smart Window 🪟
- Camera 📷
- Siren 🚨
- Smartphone 📱

All devices are connected and controlled through the IoE server.

---

## 🔄 How the System Works
1. ISP router assigns IP addresses via DHCP
2. Cloud connects different network types
3. Home gateway provides wireless access
4. IoE server manages all smart devices
5. Users control devices via IoE application

---

## 📁 Project Structure  
IoE-Network-Lab/
│── IoE_Project.pkt
│── README.md
│── configs/
│ ├── isp-router.txt
│ ├── home-gateway.txt
│ ├── iot-server.txt
│── screenshots/
│ ├── topology.png


---

## 🚀 How to Run the Project
1. Open Cisco Packet Tracer
2. Load the file `IoE_Project.pkt`
3. Ensure all devices are powered on
4. Check DHCP assignment
5. Open IoE Monitor application
6. Verify device connectivity

---

## 🎯 Learning Outcomes
- Understanding IoE architecture
- DHCP & DNS configuration
- Wireless network setup
- IoT device integration
- Network simulation using Packet Tracer

---

## 👩‍💻 Author
Cybersecurity & Network Engineering Student
