# Lab 4: Infrastructure & Perimeter Hardening

## Objective
To reduce the attack surface of the local environment by implementing multi-layered security controls across the Operating System (OS), Wireless Perimeter, and Network Gateway.

## Technical Implementation

### 1. OS-Level Access Control (POSIX Hardening)
* **Action:** Configured restricted directory permissions using the Linux CLI.
* **Control:** Applied `chmod 700` to sensitive directories, ensuring only the owner has read, write, and execute authority.
* **Evidence:** `Lab 4 - System & Infrastructure Hardening.png`

### 2. Wireless Perimeter Stealth
* **Action:** Disabled SSID broadcasting for the "Asynchronous" wireless network.
* **Control:** Perimeter Suppression mitigate unauthorized network discovery and targeted reconnaissance.
* **Evidence:** `Lab 4B - SSID Stealth Configuration.png`

### 3. Layer 2 Hardware Gatekeeping
* **Action:** Deployed a strict MAC Address Whitelist on the Huawei ONT.
* **Control:** Filter Mode set to "Whitelist" to ensure only pre-authorized hardware can associate with the Access Point.
* **Evidence:** `Lab 4C - MAC Whitelist Hardening.png`

### 4. Layer 7 Policy & Content Filtering
* **Action:** Implemented administrative content filtering and temporal access schedules.
* **Control:** Configured a "kid" template to prohibit access to specific domains (tiktok.com) and restrict network availability to a defined window (05:00-22:00).
* **Evidence:** `Lab 4D - Administrative Content Filtering.png`

---
*This module demonstrates the ability to enforce the Principle of Least Privilege and establish a defense-in-depth posture at the network edge.*
