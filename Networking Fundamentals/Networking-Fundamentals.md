# Networking Fundamentals

## What is a Network?

A network is a group of two or more devices or systems that are connected so they can communicate and share information or resources.

### For example:

- Your phone and laptop connected to the same Wi-Fi form part of a network.
- Computers in an office connected together to share files and printers form a network.
- The Internet is the world's largest network, connecting billions of devices.

---

# LAN (Local Area Network)

A LAN (Local Area Network) is a network that connects devices within a small geographical area, such as a home, office, school, or building. Devices in a LAN communicate using Ethernet cables or Wi-Fi, allowing them to share files, printers, and Internet access at high speed with low latency. A LAN is typically owned and managed by a single person or organization.

**Non-tech example:** Think of your home, where your phone, laptop, smart TV, and printer are all connected to the same Wi-Fi and can communicate with each other—that is a LAN.

---

# WAN (Wide Area Network)

A WAN (Wide Area Network) is a network that connects multiple LANs spread across different cities, states, or even countries. It enables users in different locations to communicate and access shared resources through technologies such as leased lines, VPNs, or the Internet. WANs usually have higher latency than LANs because data travels over much longer distances.

**Non-tech example:** Imagine your family members living in Pune, Mumbai, and Bangalore. Each house has its own Wi-Fi (LAN), and when everyone connects through phone or video calls, those separate homes are effectively communicating over a WAN.

---

# Internet

The Internet is the world's largest public network and is often called a network of networks because it connects millions of private and public networks across the globe. It allows billions of devices to communicate using standard protocols like TCP/IP, making services such as websites, email, cloud computing, and online streaming possible. No single organization owns the Internet; it operates through the cooperation of Internet Service Providers (ISPs) and network operators worldwide.

**Non-tech example:** Think of the Internet as a vast network of public roads that connects every city and town, allowing people to travel anywhere, while each city's internal streets represent its own local network (LAN).

---

# OSI Model (Open Systems Interconnection Model)

The OSI Model is a 7-layer conceptual framework that explains how data travels from one device to another over a network. Each layer has a specific responsibility, and together they ensure that communication between different systems happens reliably. Although modern networks primarily use the TCP/IP model, the OSI model is widely used for learning, troubleshooting, and understanding networking concepts.

## Easy Way to Remember

### Top to Bottom

> **All People Seem To Need Data Processing**

(Application → Presentation → Session → Transport → Network → Data Link → Physical)

### Bottom to Top

> **Please Do Not Throw Sausage Pizza Away**

(Physical → Data Link → Network → Transport → Session → Presentation → Application)

---

## 1. Application Layer

This is the topmost layer of the OSI model where users directly interact with network services. It provides services for applications such as web browsing, email, file transfer, and remote login.

---

## 2. Presentation Layer

This layer is responsible for translating, encrypting/decrypting, and compressing data. It ensures that data sent by one device can be correctly understood by another.

---

## 3. Session Layer

The Session layer establishes, manages, and terminates communication sessions between two devices. It keeps the connection active until the communication is complete.

---

## 4. Transport Layer

This layer ensures reliable and error-free delivery of data between devices. It breaks data into segments, performs error checking, and reassembles the data at the destination using protocols like TCP and UDP.

---

## 5. Network Layer

The Network layer determines the best path for data to travel across different networks. It uses IP addresses to route packets from the source to the destination.

---

## 6. Data Link Layer

This layer is responsible for communication between devices on the same local network. It uses MAC addresses, detects transmission errors, and controls access to the physical medium.

---

## 7. Physical Layer

The Physical layer is the lowest layer of the OSI model. It transmits raw bits as electrical, optical, or radio signals through cables, fiber optics, or wireless media.

---

# TCP/IP Model (Transmission Control Protocol/Internet Protocol)

The TCP/IP Model is the practical networking model used on the Internet today. It defines how data is transmitted between devices over a network. Unlike the OSI model, which has 7 layers, the TCP/IP model has 4 layers and is the foundation of modern networking, including the Internet, cloud platforms like AWS, and enterprise networks.

---

## 1. Application Layer

The Application layer is the topmost layer of the TCP/IP model. It provides network services directly to user applications such as web browsers, email clients, file transfer tools, and DNS. It combines the functions of the OSI Application, Presentation, and Session layers.

---

## 2. Transport Layer

The Transport layer is responsible for end-to-end communication between devices. It ensures reliable data delivery, error checking, flow control, and segmentation using protocols like TCP and UDP.

---

## 3. Internet Layer

The Internet layer handles logical addressing and routing of data packets between different networks. It uses IP addresses to determine the best path for data to reach its destination.

---

## 4. Network Access (Link) Layer

The Network Access layer is responsible for transmitting data over the physical network. It handles communication with network hardware, uses MAC addresses for local delivery, and includes technologies such as Ethernet, Wi-Fi, and ARP.

---

# IP Addressing (IPv4 & IPv6)

**IP Addressing** is the process of assigning a unique address to every device on a network so that devices can identify and communicate with each other.

---

## IPv4 (Internet Protocol Version 4)

IPv4 uses a **32-bit** address, represented in **four decimal numbers** separated by dots (e.g., `192.168.1.10`). It supports approximately **4.3 billion unique addresses**, which has become insufficient due to the rapid growth of internet-connected devices.

**Example:** `192.168.1.10`

---

## IPv6 (Internet Protocol Version 6)

IPv6 uses a **128-bit** address, represented in **eight groups of hexadecimal numbers** separated by colons (e.g., `2001:db8::1`). It provides an almost unlimited number of unique IP addresses and offers improved security, efficiency, and scalability.

**Example:** `2001:0db8:85a3:0000:0000:8a2e:0370:7334`

---

## Key Difference

- **IPv4:** 32-bit, dotted decimal notation, ~4.3 billion addresses.
- **IPv6:** 128-bit, hexadecimal notation, virtually unlimited addresses.
