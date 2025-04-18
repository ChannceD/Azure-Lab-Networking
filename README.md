
# ☁️ Azure Lab: Compute & Networking

This lab explores core Azure concepts related to compute resources and networking. It includes provisioning virtual machines (VMs), configuring remote access, analyzing network traffic, and observing DNS and DHCP in action. These exercises demonstrate my understanding of cloud infrastructure and network fundamentals.

---

## 🖼️ Lab Overview (Screenshots + Descriptions)

### 1. Creating Resource Groups
![Created resource groups](Azure%20lab%20Compute%20and%20Netwroking/Created%20resource%20groups%20.png)

We start by creating **Azure Resource Groups**, which act as containers to manage and organize related cloud resources.

---

### 2. Deploying Virtual Machines
![Created computers](Azure%20lab%20Compute%20and%20Netwroking/created%20computers%20.png)

Next, we deploy Windows virtual machines into Azure. These will be used to test connectivity and network traffic.

---

### 3. Connecting via RDP
![RDP Connection](Azure%20lab%20Compute%20and%20Netwroking/Connection%20with%20RDP.png)

Using **Remote Desktop Protocol (RDP)**, we securely connect to one of our VMs from a local system. This simulates real-world remote administration.

---

### 4. Observing RDP Traffic
![RDP Traffic](Azure%20lab%20Compute%20and%20Netwroking/RDP%20TRAFFIC.png)

Using tools like Wireshark, we monitor the network and observe traffic related to the RDP session. This helps identify how remote connections behave on a network.

---

### 5. Observing SSH Traffic
![SSH Traffic](Azure%20lab%20Compute%20and%20Netwroking/ssh%20traffic%20.png)

We perform a similar analysis with **SSH**, the secure shell protocol. Monitoring this traffic helps illustrate the encryption and communication patterns of secure remote access.

---

### 6. DNS Lookup Demonstration
![DNS Disney](Azure%20lab%20Compute%20and%20Netwroking/dns%20Disney.png)

A DNS request is made to resolve a domain name (e.g., `disney.com`). This demonstrates how Azure VMs handle domain resolution through configured DNS servers.

---

### 7. DHCP Observation
![DHCP 1](Azure%20lab%20Compute%20and%20Netwroking/DHCP%201%20.png)

Here we observe the **DHCP (Dynamic Host Configuration Protocol)** in action, as a client requests and receives an IP configuration from the Azure DHCP server.

---

### 8. PowerShell Ping Test
![PowerShell Ping](Azure%20lab%20Compute%20and%20Netwroking/Powershell%20ping.png)

Using PowerShell, we execute a `ping` test to verify communication between resources on the network.

---

### 9. Wireshark Packet Capture
![Wireshark Windows VM](Azure%20lab%20Compute%20and%20Netwroking/Windows%20vm%20wireshark.png)

A **packet capture** from a Windows VM reveals detailed network activity. This view provides visibility into protocol exchanges and potential troubleshooting insights.

---

## 🚀 Skills Demonstrated

- Azure Resource Group & VM provisioning
- Remote connectivity via RDP and SSH
- DNS and DHCP operations
- Basic PowerShell networking
- Network traffic capture and analysis (Wireshark)
- Understanding of secure and observable network protocols

---

## 💼 Why This Matters

Cloud computing and networking are foundational to modern IT. This lab shows my ability to deploy and manage cloud resources, diagnose connectivity issues, and analyze traffic flow — all essential skills for IT support and cloud admin roles.

---
