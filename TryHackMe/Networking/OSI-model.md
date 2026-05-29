# OSI Model - TryHackMe

## Overview
This room introduced the OSI (Open Systems Interconnection) Model and explained how network communication is divided into seven layers.

The OSI model helps standardize communication between systems and makes networking easier to understand and troubleshoot.

---

## Topics Learned

- OSI Model basics
- The 7 OSI layers
- Data flow in networking
- Encapsulation
- Network communication process

---

# What is the OSI Model?

The OSI Model is a conceptual framework used to understand how data travels across a network.

It divides networking into 7 layers, each responsible for specific tasks.

---

# The 7 Layers of the OSI Model

## 7. Application Layer

Responsible for:
- user interaction
- network services
- applications

Examples:
- HTTP
- HTTPS
- FTP
- DNS

---

## 6. Presentation Layer

Responsible for:
- data formatting
- encryption
- compression

Ensures data is readable between systems.

---

## 5. Session Layer

Responsible for:
- creating sessions
- maintaining connections
- terminating sessions

Manages communication between devices.

---

## 4. Transport Layer

Responsible for:
- reliable data transfer
- segmentation
- flow control
- error checking

Protocols:
- TCP
- UDP

---

## 3. Network Layer

Responsible for:
- logical addressing
- routing
- packet forwarding

Uses IP addresses.

Protocol Example:
- IP

Device:
- Router

---

## 2. Data Link Layer

Responsible for:
- MAC addressing
- local network communication
- error detection

Device:
- Switch

---

## 1. Physical Layer

Responsible for:
- physical transmission of data
- cables
- signals
- hardware

Examples:
- Ethernet cables
- Wi-Fi signals

---

# Encapsulation

As data moves down the OSI layers:
- headers are added at each layer.

When data reaches the destination:
- layers remove headers step-by-step.

This process is called encapsulation and decapsulation.

---

# Key Takeaways

- The OSI Model divides networking into 7 layers.
- Each layer has specific responsibilities.
- Understanding the OSI Model helps in troubleshooting and cybersecurity analysis.
- TCP and UDP operate at the Transport Layer.
- Routers work mainly at Layer 3 and switches at Layer 2.

---

## Status
Completed successfully on TryHackMe.
