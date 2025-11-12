# 🌐 TCP/IP Model — Networking Basics

## 📘 What is TCP/IP?

**TCP/IP** stands for  
> **Transmission Control Protocol / Internet Protocol**

It’s **a set of communication protocols** used to connect network devices on the Internet.  
TCP/IP defines **how data should be packaged, addressed, transmitted, routed, and received**.

In short —  
> TCP/IP makes sure that your data **gets to the right place, in the right order, without errors.**

---

## 🧱 The 4 Layers of the TCP/IP Model

| Layer | Name | Function | Example Protocols |
|--------|-------|-----------|------------------|
| **4** | **Application Layer** | Provides services to end users (like browsers, emails, etc.). | HTTP, HTTPS, FTP, SMTP, DNS |
| **3** | **Transport Layer** | Splits data into segments and ensures correct delivery. | TCP, UDP |
| **2** | **Internet Layer** | Handles addressing and routing through IP addresses. | IP, ICMP, ARP |
| **1** | **Network Access Layer** | Deals with physical data transmission (cables, Wi-Fi). | Ethernet, Wi-Fi, MAC |

---

## ⚙️ TCP vs IP

| Protocol | Function | Example |
|-----------|-----------|----------|
| **IP (Internet Protocol)** | Responsible for **addressing and routing** packets between devices. | Like a **home address** on a letter. |
| **TCP (Transmission Control Protocol)** | Ensures **reliable delivery** — checks that all packets arrive in order and resends any lost ones. | Like a **mailman** who confirms the delivery. |

> 💡 **Example:**  
> When you visit a website,  
> - **IP** finds where the server is.  
> - **TCP** makes sure the webpage arrives completely and correctly.

---

## ⚡ TCP vs UDP

| Feature | **TCP** | **UDP** |
|----------|----------|----------|
| **Reliability** | Reliable — guarantees delivery and correct order | Unreliable — some packets may be lost |
| **Speed** | Slower due to error checking | Faster |
| **Use Cases** | Web, Email, File Transfer | Streaming, Gaming, Voice Calls |
| **Examples** | HTTP, HTTPS | DNS, VoIP |

---

## 📦 Example Workflow

When you open your browser and type:  
`www.google.com`

1. **DNS (Application Layer)** translates the domain name to an IP address.  
2. **IP (Internet Layer)** locates the destination server.  
3. **TCP (Transport Layer)** divides the request into segments and sends them in order.  
4. **Ethernet/Wi-Fi (Network Access Layer)** transmits the data over the physical network.

---

## 🧠 Summary

- **TCP/IP** = foundation of all internet communication.  
- Consists of **4 layers** that work together to send and receive data.  
- **TCP** ensures reliability.  
- **IP** ensures correct addressing.  
- **UDP** trades reliability for speed.

