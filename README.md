# Nmap Network Scanning Lab

## Overview

This project demonstrates the use of Nmap to perform network reconnaissance in a controlled cybersecurity laboratory environment.

The scans were performed using a Kali Linux virtual machine against a Metasploitable virtual machine configured on an isolated VirtualBox internal network.

No external systems or production networks were scanned.

---

## Objectives

- Understand different Nmap scan techniques
- Compare scan results
- Learn when each scan is appropriate
- Analyse network services
- Practice ethical penetration testing techniques

---

## Lab Environment

### Attacker Machine

- Kali Linux
- Nmap

### Target Machine

- Metasploitable

### Virtualization

- Oracle VirtualBox
- Internal Network Only

---

## Scans Performed

### TCP SYN (Stealth) Scan

Command

```bash
nmap -sS <Target-IP>
```

Purpose

Performs a half-open TCP scan that is fast and less likely to be logged.

---

### TCP Connect Scan

Command

```bash
nmap -sT <Target-IP>
```

Purpose

Performs a complete TCP connection using the operating system networking stack.

---

### UDP Scan

Command

```bash
nmap -sU <Target-IP>
```

Purpose

Identifies open UDP services running on the target system.

---

### ACK Scan

Command

```bash
nmap -sA <Target-IP>
```

Purpose

Determines firewall filtering rules rather than identifying open ports.

---

## Key Skills Demonstrated

- Kali Linux
- Nmap
- Network Reconnaissance
- TCP/IP
- UDP
- Port Scanning
- Cybersecurity Documentation
- Virtual Machine Networking

---

## Screenshots

The Screenshots folder contains:

- Network Configuration
- Stealth Scan
- TCP Connect Scan
- UDP Scan
- ACK Scan

