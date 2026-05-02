Got it — I’ll write a **GitHub README** for your **IP Routing (GNS3) case study project** similar style to your SIEM one so it looks consistent in your portfolio.

---

# 🌐 Enterprise Network Routing Simulation (GNS3)

## 📌 Overview

This project focuses on the design, configuration, and troubleshooting of an **enterprise-level network routing environment** using **GNS3 simulation**.

The network simulates real-world scenarios involving multiple routing protocols such as **EIGRP, OSPF, and BGP**, along with advanced networking features like **route redistribution, GRE tunneling, DHCP, and Policy-Based Routing (PBR)**.

The objective is to ensure **end-to-end connectivity, optimized routing paths, and network resilience** across multiple domains. 

---

## 🎯 Objectives

* Configure and manage multiple routing protocols (EIGRP, OSPF, BGP)
* Implement inter-domain routing and route redistribution
* Optimize routing using summarization and path manipulation
* Ensure network redundancy and failover mechanisms
* Perform troubleshooting and validation of network connectivity

---

## 🛠️ Tools & Technologies

* **GNS3** – Network simulation platform
* **Cisco IOS** – Router configuration
* **Routing Protocols**:

  * EIGRP
  * OSPF
  * BGP (eBGP & iBGP)

---

## 🧩 Network Features Implemented

### 🔹 Dynamic Routing

* **EIGRP** for fast convergence within internal networks
* **OSPF** for scalable link-state routing
* **BGP** for inter-autonomous system communication

### 🔹 Route Redistribution

* Redistribution between EIGRP, OSPF, and BGP
* Ensures seamless communication between different routing domains

### 🔹 Route Summarization

* Aggregation of multiple routes into summarized prefixes
* Reduces routing table size and improves efficiency 

### 🔹 GRE Tunneling

* Configured GRE tunnel for secure and alternative routing paths
* Verified connectivity between endpoints

### 🔹 Path Manipulation (BGP)

* Used **Local Preference** to control traffic flow
* Influenced routing decisions for optimal path selection 

### 🔹 Policy-Based Routing (PBR)

* Controlled traffic paths based on defined policies
* Enabled advanced traffic engineering

### 🔹 DHCP Configuration

* Automatic IP address assignment for end devices
* Verified connectivity between hosts

---

## 🔍 Key Configurations

### 📡 Routing Validation Commands

* `show ip route` → Verify routing table
* `show ip eigrp neighbors` → Check EIGRP adjacency
* `show ip ospf neighbor` → Verify OSPF neighbors
* `show ip bgp` → View BGP routing table
* `show ip bgp summary` → Check BGP session status

---

## 📊 Key Results

* ✅ Successful routing between multiple autonomous systems
* ✅ Stable EIGRP and OSPF neighbor relationships established
* ✅ BGP peering (eBGP & iBGP) functioning correctly
* ✅ Route redistribution working across protocols
* ✅ Reduced routing table size through summarization
* ✅ GRE tunnel successfully established and tested
* ✅ Traffic flow optimized using path manipulation

---

## 🔐 Security Features

* BGP **MD5 Authentication** to secure peer connections
* **Prefix Filtering** to prevent route hijacking
* **Maximum Prefix Limit** to avoid route flooding
* **ACLs** to restrict unauthorized access 

---

## 🚀 Future Improvements

* Implement network automation (Python/Ansible)
* Add monitoring tools (SNMP, NetFlow)
* Integrate with SIEM for security visibility
* Expand topology for enterprise-scale simulation

---

## 📷 Topology

*(Insert your GNS3 topology screenshot here)*

---

## 👨‍💻 Author

**Khairul Azim**

* Network & Cybersecurity Enthusiast
* Aspiring SOC Analyst

---

## 📚 Learning Outcomes

* Hands-on experience with enterprise routing protocols
* Strong understanding of multi-protocol environments
* Improved troubleshooting and network design skills
* Practical exposure to real-world networking scenarios

---

If you want, I can:

* Merge both projects into **one strong cybersecurity portfolio README**
* Add **GitHub badges (skills, tools, certs like Security+)**
* Or convert this into a **resume project description (ATS-friendly)** 🚀
