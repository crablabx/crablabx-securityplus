# 🧱 Domain 3: Security Architecture

This document covers secure network and system architecture, including cloud, virtualization, and cryptographic principles, as outlined in Domain 3 of the CompTIA Security+ (SY0-701) exam.

---

## 🏗️ 3.1 Security Design Principles

- **Least Privilege** – Give users only the access they need
- **Defense in Depth** – Use multiple layers of protection
- **Zero Trust** – Never assume trust, always verify
- **Segmentation** – Divide networks to isolate threats
- **Redundancy & Fault Tolerance** – Keep services running during failures

---

## 🌐 3.2 Network Architecture Concepts

| Concept | Description |
|--------|-------------|
| **DMZ** | Public-facing area separated from internal network |
| **NAT** | Hides internal IPs from the internet |
| **VLANs** | Logically separate broadcast domains |
| **Proxy** | Forwards or filters traffic on behalf of clients |
| **VPN** | Encrypted tunnel between endpoints |

---

## ☁️ 3.3 Virtualization & Cloud Security

### 🧳 Deployment Models
- **Public Cloud** – AWS, Azure
- **Private Cloud** – Owned and operated internally
- **Hybrid Cloud** – Combination of both

### 🔐 Cloud Concerns
- **Data ownership**
- **Shared responsibility model**
- **Misconfigurations (e.g., open S3 buckets)**

---

## 🔐 3.4 Secure Protocols & Encryption

| Protocol | Purpose |
|----------|---------|
| **HTTPS** | Secure web traffic |
| **SSH** | Secure shell for remote access |
| **SFTP/FTPS** | Secure file transfer |
| **IPSec** | Network-layer encryption |
| **TLS** | Encrypts communications over TCP |

### 🔐 Common Encryption Concepts
- **Symmetric Encryption** – One key (e.g., AES)
- **Asymmetric Encryption** – Public/private key pair (e.g., RSA)
- **Hashing** – One-way transformation (e.g., SHA-256)

---

## 🧠 Study Tips
- Know the difference between symmetric and asymmetric encryption
- Be able to describe cloud deployment types
- Understand network isolation and architecture best practices

---

> "Good security architecture doesn’t just stop intruders — it makes them wish they never showed up."

