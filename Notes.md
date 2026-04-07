Identified my target role: Junior SOC Analyst. Why? High demand (3.5M+ roles) and aligns with my defensive security interest


# 🛡️ Cybersecurity Learning Journey (2026)
**Name:** Harimohan Sharma | **Goal:** SOC Analyst / Cloud Security

---

## 🚀 Module 1: Introduction to Cybersecurity

### 🔴 Phase 1: Offensive Security (Attacking)
**Target:** FakeBank Application
**Objective:** Identify hidden directories and exploit business logic vulnerabilities.

| Tool | Command | Purpose |
| :--- | :--- | :--- |
| `dirb` | `dirb http://url.com` | To find hidden files/folders using a wordlist. |

**Key Findings:** - Found hidden page: `/bank-transfer`.
- **Exploit:** Manipulated deposit amount to bypass logic and trigger the flag.

---

### 🔵 Phase 2: Defensive Security (Defending)
**Objective:** Monitor SOC dashboards and mitigate active threats.

- **Threat Identified:** Brute Force Attack (Repeated login failures from IP: Russia).
- **Remediation Steps:**
  1. `Containment`: Blocked the source IP address.
  2. `Prevention`: Implemented **Rate Limiting** to slow down automated attacks.
  3. `Hardening`: Updated WAF (Web Application Firewall) rules.

> **Learning:** Defense is about speed. The faster you 'Contain' the threat, the less damage occurs.

## 📍 Task 2 & 3: IP and MAC Advanced
- **Octet:** An IPv4 address is made of 4 octets (8 bits each). Total 32 bits.
- **MAC Spoofing:** Changing the hardware address (MAC) of a device temporarily to bypass network security filters.
- **Flag Captured:** [Yahan wo THM flag dalo jo tumhe lab se milega]

- ---
## 📍 Task 4: Ping (ICMP Protocol)
- **Concept:** Ping is used to check the reachability of a host on an IP network.
- **Protocol:** It uses **ICMP** (Internet Control Message Protocol).
- **Process:** 1. `Echo Request`: Humne pucha "Kya tum waha ho?"
  2. `Echo Reply`: Host ne bola "Haan, main yaha hoon."
- **Command:** `ping <IP_Address>`
- **Learning:** If ping fails, it means the host is down or ICMP is blocked by a firewall.
