# OSI Model (Open Systems Interconnection)

The **OSI Model** is a conceptual framework that standardizes how data moves across a network.  
It consists of **7 layers**, each responsible for specific networking functions.  
It is mainly used for learning, design, and troubleshooting.

---

## The 7 Layers (Top → Bottom)

| Layer | Name | Purpose | Examples |
|---|---|---|---|
| 7 | **Application** | Interfaces for applications to access network services | HTTP, HTTPS, DNS, FTP, SMTP |
| 6 | **Presentation** | Data representation, encryption, compression | TLS/SSL, Base64, JPEG, ASCII |
| 5 | **Session** | Establishing, managing, and terminating sessions | RPC, NetBIOS, Authentication Handshakes |
| 4 | **Transport** | End-to-end data delivery, reliability, ports | TCP, UDP, Port Numbers |
| 3 | **Network** | Logical addressing and routing | IP, ICMP, Routing Protocols (OSPF, BGP) |
| 2 | **Data Link** | MAC addressing, framing, VLANs, error detection | Ethernet, ARP, STP, 802.1Q VLAN |
| 1 | **Physical** | Physical transmission of raw bits | Cables, Fiber, Wi-Fi Signals, Hubs |

---

## Layer-by-Layer Explanation

### 7. Application Layer
Provides network services directly to end-user applications.  
Examples: Web browsers, email clients, DNS lookups.

### 6. Presentation Layer
Formats and transforms data to ensure compatibility:
- Encryption / Decryption (e.g., TLS/SSL)
- Compression
- Encoding (text, images, binary)

### 5. Session Layer
Manages **sessions** between devices:
- Opening, maintaining, and closing communication sessions
- Checkpointing and recovery

### 4. Transport Layer
Controls **reliable** or **unreliable** communication:
- **TCP** → reliable, connection-based
- **UDP** → fast, connectionless
Also manages **port numbers** (e.g., 80, 443, 22).

### 3. Network Layer
Responsible for **routing** and **IP addressing**:
- Moves packets between different networks
- Determines the best path to destination

### 2. Data Link Layer
Handles **MAC addresses**, frame creation, switching, and basic error detection.
Examples:
- Switches operate here
- ARP resolves IP ↔ MAC

### 1. Physical Layer
Transmits raw **bits** as electrical or radio signals:
- Cables (Cat5/Cat6), Fiber, Wi-Fi radio waves
- Network speed and signal integrity



