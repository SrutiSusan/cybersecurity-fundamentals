# Cybersecurity Core Concepts
**Prepared by:** Sruti Susan Shaji | ISO/IEC 27001:2022 Certified Lead Auditor  
**Date:** June 2026

---

## The CIA Triad

The CIA Triad is the foundation of information security. 
Every security control, risk, and threat can be mapped back 
to one or more of these three principles.

---

### 1. Confidentiality
Ensuring information is accessible only to those authorised to access it.

**Examples of controls:**
- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- Data encryption
- Need-to-know access policies

**Common threats:**
- Phishing attacks
- Unauthorised access
- Data leakage

**Real world example:**
Restricting customer payment data access to only the finance 
team — not all employees.

---

### 2. Integrity
Ensuring information is accurate, complete, and has not been 
tampered with.

**Examples of controls:**
- Hash verification
- Audit logs and activity monitoring
- Change management processes
- Digital signatures

**Common threats:**
- Man-in-the-middle attacks
- Insider tampering
- Malware modifying files

**Real world example:**
Maintaining audit logs of all changes made to customer orders 
to detect unauthorised modifications.

---

### 3. Availability
Ensuring information and systems are accessible when needed 
by authorised users.

**Examples of controls:**
- Regular data backups
- Disaster recovery planning
- Redundant systems
- Incident response procedures

**Common threats:**
- Ransomware attacks
- System failures
- Denial of Service (DoS) attacks

**Real world example:**
Maintaining daily automated backups so the eCommerce platform 
can be restored quickly after a system failure.

---

## Common Threat Categories

| Threat | Description | CIA Impact |
|--------|-------------|------------|
| Phishing | Deceptive emails tricking users into revealing credentials | Confidentiality |
| Ransomware | Malware encrypting data and demanding payment | Availability, Integrity |
| Insider Threat | Malicious or accidental actions by employees | All three |
| Man-in-the-Middle | Attacker intercepts communication between two parties | Confidentiality, Integrity |
| Social Engineering | Manipulating people into revealing sensitive information | Confidentiality |
| DoS/DDoS Attack | Overwhelming a system to make it unavailable | Availability |

---

## Access Control Types

| Type | Description | Example |
|------|-------------|---------|
| **RBAC** | Role-Based Access Control — access based on job role | Finance team accesses payment data only |
| **DAC** | Discretionary Access Control — owner controls access | File owner grants access to colleagues |
| **MAC** | Mandatory Access Control — system enforces access rules | Government classified document access |
| **MFA** | Multi-Factor Authentication — multiple verification steps | Password + OTP code |

---

## Authentication vs Authorisation

| Concept | Meaning | Example |
|---------|---------|---------|
| **Authentication** | Verifying who you are | Logging in with username and password |
| **Authorisation** | Verifying what you can access | Admin vs standard user permissions |

---

## Encryption Basics

| Term | Meaning |
|------|---------|
| **Encryption** | Converting data into unreadable format to prevent unauthorised access |
| **Decryption** | Converting encrypted data back to readable format |
| **TLS/SSL** | Protocols securing data in transit — e.g. HTTPS websites |
| **AES** | Advanced Encryption Standard — widely used for data at rest |

---

## Security Frameworks at a Glance

| Framework | Purpose |
|-----------|---------|
| **ISO/IEC 27001:2022** | International standard for ISMS — governance and risk management |
| **NIST CSF** | US framework covering Identify, Protect, Detect, Respond, Recover |
| **CIS Controls** | Prioritised set of actions to protect against common cyber attacks |

---

*These concepts form the foundational knowledge base for GRC 
practice, risk assessment, and ISO 27001 audit work.*
