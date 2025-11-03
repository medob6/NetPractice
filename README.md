<h1 align="center">🌐 42 NetPractice</h1>
<p align="center">
  <b>Networking Fundamentals – 42 School Project</b><br/>
  <i>Learn IP addressing, subnetting, and routing through interactive exercises.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/School-42-black?style=flat-square&logo=42" />
  <img src="https://img.shields.io/badge/Language-Networking-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Finished-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Score-100%2F100-brightgreen?style=flat-square" />
</p>

---

## 📘 Project Overview

**NetPractice** is a **42 School project** designed to teach the **basics of computer networking**.  
You’ll configure a series of virtual networks to make all devices communicate successfully by applying concepts like **IP addressing**, **subnetting**, and **routing**.

Through practical exercises, you’ll move from simple two-device connections to multi-router setups with multiple subnets.

---

## 🧠 Learning Objectives

- Understand the structure of **IPv4 addresses**
- Learn how **subnet masks** define network ranges  
- Configure **routers, switches, and gateways**
- Apply **routing table logic** to interconnect networks  
- Troubleshoot connectivity using IP logic

---

## 🧩 Topics Covered

| Module | Concept | Key Focus |
|:------:|:---------|:----------|
| 1 | Basic IP addressing | Network vs. host bits |
| 2 | Subnetting | CIDR notation, address ranges |
| 3 | Switches | LAN communication |
| 4 | Routers | Connecting separate networks |
| 5 | Routing tables | Default routes, next hops |
| 6–10 | Full network logic | Combined problem solving |

---

## ⚙️ How to Use

1. Access the [**NetPractice platform**](https://netpractice.fr/)
2. Log in with your **42 intranet credentials**
3. For each level:
   - Assign IP addresses and subnet masks correctly
   - Configure routers and interfaces logically
   - Validate connectivity between all nodes

When all devices can reach each other, you can **submit** your solution.

---

## 🧾 Key Concepts Explained

### 🖧 IP Addressing
Each device has a **unique IPv4 address**, divided into:
- **Network ID** → identifies the network
- **Host ID** → identifies the device in that network  

Example:
```
IP: 192.168.1.10
Mask: 255.255.255.0 (/24)
Network ID: 192.168.1.0
Broadcast: 192.168.1.255
Usable Range: 192.168.1.1 → 192.168.1.254
```

---

### 🧮 Subnetting
A subnet mask determines how many hosts a network can contain.  
Example:
| CIDR | Subnet Mask | # of Hosts |
|:----:|:-------------|:-----------|
| /30 | 255.255.255.252 | 2 |
| /29 | 255.255.255.248 | 6 |
| /24 | 255.255.255.0 | 254 |

---

### 🚦 Routing Tables
A **router** decides where to send packets based on its **routing table**.

| Destination | Next Hop | Interface |
|--------------|-----------|-----------|
| 0.0.0.0/0 (default) | 192.168.0.1 | eth0 |
| 10.0.0.0/24 | 10.0.0.2 | eth1 |

Each router must know where to send packets for networks it doesn’t directly connect to.

---

## 🧭 Tips for Solving Levels

- Double-check **IP ranges** and **masks**
- Avoid **overlapping subnets**
- Routers must connect **different networks**
- Each interface of a router belongs to a **separate network**
- Always **test connectivity** both ways

---

## 📚 Resources

- [**Cisco Networking Academy**](https://www.netacad.com/)
- [**Subnet Cheat Sheet**](https://www.pcwdld.com/subnet-cheat-sheet)
- [**Wikipedia – IP Addressing**](https://en.wikipedia.org/wiki/IP_address)
- [**RFC 791 – Internet Protocol**](https://datatracker.ietf.org/doc/html/rfc791)
- 42 Intranet documentation for **NetPractice**

---

## 🧑‍💻 Author

**mohamed boussetta**  
📍 42 [1337 benguerir]  
📧 [mbousset@student.1337.ma] 
🌐 [github.com/medob6](https://github.com/medob6)

---

## 🏁 Final Score

<p align="center">
  <img src="https://img.shields.io/badge/Score-100%2F100-brightgreen?style=for-the-badge" />
</p>

---

> _“Networking is not about memorization — it’s about logic, structure, and communication.”_ 🌐

