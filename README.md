# 🌐 OSI Model (Open Systems Interconnection)

<div align="center">

![OSI Model](https://img.shields.io/badge/Networking-OSI%20Model-blue?style=for-the-badge)
![Layers-7-success?style=for-the-badge](https://img.shields.io/badge/Layers-7-success?style=for-the-badge)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Essential-red?style=for-the-badge)

### **The Foundation of Computer Networking**

*"Every piece of data sent over a network passes through these 7 layers."*

</div>

---

# 📖 What is the OSI Model?

The **OSI (Open Systems Interconnection) Model** is a **7-layer networking reference model** developed by the **International Organization for Standardization (ISO)**.

It explains **how data travels from one device to another** over a network by dividing the communication process into seven separate layers.

### 🎯 Why is the OSI Model Important?

* Understands how computer networks work.
* Helps troubleshoot network issues.
* Standardizes communication between different devices.
* Forms the foundation of networking and cybersecurity.

---

# 🏗️ OSI Model Structure

```text
+-------------------------+
| 7. Application Layer    |
+-------------------------+
| 6. Presentation Layer   |
+-------------------------+
| 5. Session Layer        |
+-------------------------+
| 4. Transport Layer      |
+-------------------------+
| 3. Network Layer        |
+-------------------------+
| 2. Data Link Layer      |
+-------------------------+
| 1. Physical Layer       |
+-------------------------+
```

---

# 📚 The 7 Layers Explained

## 🔹 Layer 7 — Application Layer

### Purpose

Provides network services directly to end users and applications.

### Responsibilities

* Web browsing
* Email
* File transfer
* DNS lookup

### Common Protocols

* HTTP / HTTPS
* FTP
* SMTP
* POP3 / IMAP
* DNS
* SSH

### Real-Life Example

When you open **Google Chrome** and visit **google.com**, the Application Layer starts the communication.

---

## 🔹 Layer 6 — Presentation Layer

### Purpose

Converts data into a format both devices can understand.

### Responsibilities

* Encryption
* Decryption
* Compression
* Data formatting

### Examples

* SSL/TLS
* JPEG
* PNG
* MP3
* GIF

### Real-Life Example

When you open an **HTTPS website**, TLS encrypts the communication at this layer.

---

## 🔹 Layer 5 — Session Layer

### Purpose

Creates, manages, and terminates communication sessions.

### Responsibilities

* Session establishment
* Authentication
* Session synchronization
* Session termination

### Protocol Examples

* NetBIOS
* RPC
* SMB Session

### Real-Life Example

A Zoom or Microsoft Teams meeting remains active because the Session Layer maintains the connection.

---

## 🔹 Layer 4 — Transport Layer

### Purpose

Ensures reliable or fast delivery of data.

### Responsibilities

* Segmentation
* Error checking
* Flow control
* Reliable communication

### Protocols

* TCP
* UDP

### Devices

* Firewall
* Load Balancer

### Real-Life Example

Downloading a file uses **TCP** because every packet must arrive correctly.

Streaming video often uses **UDP** because speed is more important than perfect delivery.

---

## 🔹 Layer 3 — Network Layer

### Purpose

Finds the best path between source and destination.

### Responsibilities

* Logical Addressing
* Routing
* Path Selection

### Protocols

* IP
* ICMP
* IPSec

### Device

* Router

### Real-Life Example

Google Maps finds the best route for you.

Similarly, routers find the best path for packets.

---

## 🔹 Layer 2 — Data Link Layer

### Purpose

Transfers data between devices on the same local network.

### Responsibilities

* MAC Addressing
* Error Detection
* Frame Delivery

### Protocols

* Ethernet
* ARP
* PPP

### Device

* Switch

### Real-Life Example

A switch delivers data to the correct computer inside your office LAN.

---

## 🔹 Layer 1 — Physical Layer

### Purpose

Transmits raw bits over physical media.

### Responsibilities

* Electrical signals
* Optical signals
* Radio signals

### Devices

* Hub
* Cable
* Fiber
* Repeater

### Real-Life Example

Ethernet cables, Wi-Fi signals, and fiber optic cables all operate at this layer.

---

# 📦 Data Encapsulation

When data is sent through the network:

```text
Application
      ↓
Presentation
      ↓
Session
      ↓
Transport
      ↓
Network
      ↓
Data Link
      ↓
Physical
```

At the receiver:

```text
Physical
      ↑
Data Link
      ↑
Network
      ↑
Transport
      ↑
Session
      ↑
Presentation
      ↑
Application
```

---

# 📦 Protocol Data Units (PDU)

| Layer        | PDU                            |
| ------------ | ------------------------------ |
| Application  | Data                           |
| Presentation | Data                           |
| Session      | Data                           |
| Transport    | Segment (TCP) / Datagram (UDP) |
| Network      | Packet                         |
| Data Link    | Frame                          |
| Physical     | Bits                           |

---

# 🖥️ Devices by Layer

| Layer        | Device       |
| ------------ | ------------ |
| Application  | Proxy Server |
| Presentation | SSL Gateway  |
| Session      | Gateway      |
| Transport    | Firewall     |
| Network      | Router       |
| Data Link    | Switch       |
| Physical     | Hub, Cable   |

---

# 🌍 Real-Life Example

Imagine you send a WhatsApp message:

1. **Application** → You type the message.
2. **Presentation** → Message is encrypted.
3. **Session** → Chat session is maintained.
4. **Transport** → TCP/UDP sends the data.
5. **Network** → IP chooses the best route.
6. **Data Link** → Switch sends it within the local network.
7. **Physical** → Bits travel through Wi-Fi or Ethernet.

The receiver performs the reverse process to display the message.

---

# 🔐 OSI Model in Cybersecurity

| Layer        | Security Examples           |
| ------------ | --------------------------- |
| Application  | SQL Injection, XSS          |
| Presentation | SSL/TLS Encryption          |
| Session      | Session Hijacking           |
| Transport    | TCP/UDP Attacks             |
| Network      | IP Spoofing, ICMP Attacks   |
| Data Link    | ARP Spoofing, MAC Flooding  |
| Physical     | Cable Tapping, Device Theft |

---

# 🧠 Easy Mnemonics

## Top → Bottom

```text
All
People
Seem
To
Need
Data
Processing
```

---

## Bottom → Top

```text
Please
Do
Not
Throw
Sausage
Pizza
Away
```

---

# 🎯 Interview Questions

### Q1. What is the OSI Model?

A networking reference model consisting of **7 layers** that explains how data travels between devices.

---

### Q2. Which layer uses IP addresses?

**Network Layer (Layer 3)**

---

### Q3. Which layer uses MAC addresses?

**Data Link Layer (Layer 2)**

---

### Q4. Which layer is responsible for routing?

**Network Layer (Layer 3)**

---

### Q5. Which layer uses TCP and UDP?

**Transport Layer (Layer 4)**

---

### Q6. Which layer does DNS work on?

**Application Layer (Layer 7)**

---

### Q7. Which device works at Layer 2?

**Switch**

---

### Q8. Which device works at Layer 3?

**Router**

---

# 📋 Quick Revision

| Layer | Name         | Main Work                  |
| ----- | ------------ | -------------------------- |
| 7     | Application  | User Services              |
| 6     | Presentation | Encryption & Formatting    |
| 5     | Session      | Session Management         |
| 4     | Transport    | TCP/UDP, Reliable Delivery |
| 3     | Network      | IP Address & Routing       |
| 2     | Data Link    | MAC Address & Switching    |
| 1     | Physical     | Bits, Cables, Signals      |

---

# 💡 Key Takeaways

* OSI stands for **Open Systems Interconnection**.
* It consists of **7 layers**.
* Each layer has a specific responsibility.
* Data is **encapsulated** while sending and **decapsulated** while receiving.
* Understanding the OSI model is essential for **Networking**, **Cybersecurity**, **Ethical Hacking**, and **Network Troubleshooting**.

---

<div align="center">

### ⭐ If you found these notes useful, don't forget to Star this repository!

**Made with ❤️ by Ujjwal Kumar**

</div>
