# 🌐 Networking Protocols — Categorized Overview

This document groups the most important **networking protocols** by their **category** (or layer) in the **TCP/IP model**.

---

## 🧱 1. Application Layer Protocols

These protocols allow **user applications** (like browsers and email clients) to interact with the network.

| Protocol | Full Name | Function / Usage |
|-----------|------------|------------------|
| **HTTP** | HyperText Transfer Protocol | Transfers web pages between client and server. |
| **HTTPS** | HTTP Secure | Same as HTTP, but encrypted with SSL/TLS for secure communication. |
| **FTP** | File Transfer Protocol | Transfers files between computers (upload/download). |
| **SFTP** | Secure File Transfer Protocol | Secure version of FTP using SSH encryption. |
| **SMTP** | Simple Mail Transfer Protocol | Sends outgoing emails from client to mail server. |
| **POP3** | Post Office Protocol v3 | Retrieves emails from a mail server (downloads messages). |
| **IMAP** | Internet Message Access Protocol | Accesses and manages emails on a mail server (keeps them online). |
| **DNS** | Domain Name System | Converts domain names (like google.com) into IP addresses. |
| **DHCP** | Dynamic Host Configuration Protocol | Automatically assigns IP addresses to devices on a network. |
| **SNMP** | Simple Network Management Protocol | Used to monitor and manage network devices (like routers, switches). |
| **NTP** | Network Time Protocol | Synchronizes time between computers. |

---

## 🔄 2. Transport Layer Protocols

These protocols manage **data delivery** between devices — ensuring it’s sent, received, and ordered properly.

| Protocol | Full Name | Function / Usage |
|-----------|------------|------------------|
| **TCP** | Transmission Control Protocol | Reliable, connection-oriented protocol that ensures data arrives in order and without loss. |
| **UDP** | User Datagram Protocol | Fast, connectionless protocol that doesn’t guarantee delivery (used for streaming, gaming, etc.). |

---

## 🌍 3. Internet Layer Protocols

These handle **addressing, routing, and packet delivery** across networks.

| Protocol | Full Name | Function / Usage |
|-----------|------------|------------------|
| **IP** | Internet Protocol | Defines addressing and routing of packets across networks. |
| **IPv4** | Internet Protocol Version 4 | 32-bit addressing (e.g. 192.168.1.1). |
| **IPv6** | Internet Protocol Version 6 | 128-bit addressing (supports more devices). |
| **ICMP** | Internet Control Message Protocol | Used for testing and error reporting (e.g. `ping` command). |
| **ARP** | Address Resolution Protocol | Maps an IP address to a MAC address on a local network. |
| **RARP** | Reverse Address Resolution Protocol | Maps a MAC address to an IP address (reverse of ARP). |

---

## ⚙️ 4. Network Access Layer Protocols

These control **how data is physically sent** through cables or wireless signals.

| Protocol | Full Name | Function / Usage |
|-----------|------------|------------------|
| **Ethernet (IEEE 802.3)** | — | Standard for wired LAN connections. |
| **Wi-Fi (IEEE 802.11)** | — | Standard for wireless LAN communication. |
| **PPP** | Point-to-Point Protocol | Used for direct connections (modems, serial links). |
| **HDLC** | High-Level Data Link Control | Encapsulation protocol used in WANs. |
| **Frame Relay** | — | Used for WAN data transmission. |
| **ATM** | Asynchronous Transfer Mode | High-speed data transfer protocol for telecom networks. |

---

## 📡 5. Security & Encryption Protocols

Used to **secure data** while it’s transmitted over the network.

| Protocol | Full Name | Function / Usage |
|-----------|------------|------------------|
| **SSL / TLS** | Secure Sockets Layer / Transport Layer Security | Encrypts communication between client and server (used by HTTPS). |
| **SSH** | Secure Shell | Secure remote login and file transfer. |
| **IPSec** | Internet Protocol Security | Secures IP communications by authenticating and encrypting packets. |
| **Kerberos** | — | Authentication protocol for secure network access (used in Windows domains). |

---

## 📬 6. File Sharing & Remote Access Protocols

Used for **remote management**, **file access**, and **resource sharing**.

| Protocol | Full Name | Function / Usage |
|-----------|------------|------------------|
| **RDP** | Remote Desktop Protocol | Allows remote control of Windows systems. |
| **Telnet** | — | Remote command-line access (insecure). |
| **SSH** | Secure Shell | Secure alternative to Telnet for command-line access. |
| **SMB** | Server Message Block | File and printer sharing in Windows networks. |
| **NFS** | Network File System | File sharing protocol used in Linux/Unix systems. |

---

## 🧠 Summary by Category

| Category | Examples | Main Purpose |
|-----------|-----------|---------------|
| **Application Layer** | HTTP, DNS, FTP, SMTP | User-level communication |
| **Transport Layer** | TCP, UDP | Data delivery and reliability |
| **Internet Layer** | IP, ICMP, ARP | Addressing and routing |
| **Network Access Layer** | Ethernet, Wi-Fi | Physical data transmission |
| **Security** | SSL, TLS, IPSec, SSH | Encryption and authentication |
| **Remote/File Sharing** | RDP, SMB, NFS | Remote access and resource sharing |

