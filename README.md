# 100-Days-Cybersecurity-Sprint
Objective: Transitioning into an enterprise Tier-1 SOC Analyst role within 100 days.
Daily Commitment: 11 Hours of structured technical infrastructure study, defensive hands-on lab simulations, and Python/AI automation development.
Target Location: Chennai / Bengaluru Tech Hubs (MSSPs & Consultancies).
---

## 📅 Daily Execution Tracking

### 🛡️ Day 1 & Day 2: Network Infrastructure & Systems Architecture Foundations

#### 1. Core Networking Architecture (CCNA Modules 1-6)
* **OSI vs. Modern TCP/IP Models**: Mastered the 5-Layer conceptual framework and protocol data units (PDUs). Documented structural encapsulation transformations: Data (L5) ➔ Segment (L4) ➔ Packet (L3) ➔ Frame (L2) ➔ Bits (L1).
* **Layer 2 Data Link Switching Logic**: Analyzed how a hardware switch utilizes incoming frame source MAC addresses to populate its CAM/MAC address table dynamically while leveraging destination MAC addresses to execute precise filtering, forwarding, or flooding operations.
* **Micro-Segmentation & Collision Domains**: Audited the structural shift from Half-Duplex shared collision domains (legacy hubs operating with CSMA/CD mechanisms) to isolated Full-Duplex micro-segments on modern switches, rendering data collisions impossible .
* **Cisco IOS CLI Privilege Ladder**: Documented command hierarchy navigation rules across User EXEC (`Switch>`), Privileged EXEC (`Switch#` via `enable`), and Global Configuration (`Switch(config)#` via `configure terminal`) .

#### 💻 2. Practical Lab Simulation & Systems Auditing
* **Live Network Discovery Simulation**: Provisioned a 3-node localized star topology connected to a Cisco 2960 Switch inside Cisco Packet Tracer. Switched to simulation frame analytics to observe an ARP Broadcast query (`FF:FF:FF:FF:FF:FF`) trigger a systematic switch-port flooding event .
* **CAM Memory Validation**: Formally audited the switch's internal RAM configuration via the CLI utilizing `show mac address-table` to verify dynamic MAC-to-Interface matching parameters .
* **Linux Kernel Socket Enumeration**: Logged directly into the Ubuntu sandbox kernel terminal to execute `ss -tulpn` and deployed `nmap 127.0.0.1` to track system exposures, isolating background system operations actively running on Layer 4 security channels (Port 53 DNS / Port 631 Printing Daemon) .

### 🛡️ Day 3: Advanced Network Slicing & Security Automation Logic

#### 🌅 1. Infrastructure & Subnet Engineering (CCNA Day 7 & 8)
* **IP Addressing Classes**: Documented global routing boundaries across Class A (`1-126`), Class B (`128-191`), and Class C (`192-223`) networks.
* **Custom Subnetwork Slicing (VLSM)**: Mastered the mechanics of Variable Length Subnet Masking. Studied bit-borrowing concepts to slice open network ranges into isolated, secure compartments.
* **Whiteboard Calculation Mastery**: Applied the Magic Number formula (`256 - Mask`) to solve complex subnetwork boundaries, successfully calculating absolute Network IDs, Broadcast Addresses, and usable host ranges across custom `/26`, `/27`, and `/28` CIDR bitwise layouts.

#### ☀️ 2. Operating System Security & Hardening Lab
* **OS Account Auditing**: Navigated the Linux filesystem directory to audit the core system user database file `/etc/passwd` and the restricted password hashing database file `/etc/shadow`.
* **Privilege Escalation Mitigation**: Simulated a insider threat attack by dynamically tracking user group membership, successfully appending and revoking root administrative access (`sudo` group) using `usermod` and `deluser`.
* **File System Hardening**: Implemented the Principle of Least Privilege by applying numerical absolute notations (`chmod 600`) to sensitive data files, successfully hardening configurations and validating explicit kernel-level `Permission denied` blocks against unauthorized user accounts.

#### 🌇 3.  Python Security Automation & Conditional Logic
* **Variable Architecture**: Provisioned structured memory storage containers using explicitly case-sensitive data types (Strings and Integers) to track system parameters like `ip_address` and `failed_logins`.
* **Typographical Debugging**: Successfully identified, isolated, and resolved a runtime compilation `NameError` caused by variable character casing variations.
* **Autonomous Decision Mitigation Matrix**: Programmed defensive logical branches utilizing conditional syntax (`if`, `elif`, `else`) to force the script to automatically parse system state changes and flash system lockout warnings when remaining login thresholds hit critical limits.

### 🛡️ Day 4: Hardware Interfaces, OS Daemon Auditing & Interactive Gateways

#### 1. Layer 3 Routing & Packet Anatomy (CCNA Day 9 & 10)
* **Switch Interface Management**: Mastered interface tracking structures via Cisco IOS execution parameters (`show interface status`). Analyzed duplex and speed attributes to identify and remediate link layer throughput constraints.
* **IPv4 Header Layer Dissection**: Mapped out the 32-bit wide network boundary grid layout of the Layer 3 IP header envelope (20-byte baseline packet configuration).
* **Field Component Analysis**: Deconstructed critical packet filtering fields including Version flags, Time-To-Live (TTL) loop prevention metrics, and Protocol payload markers (`1` for ICMP, `6` for TCP, `17` for UDP) to build programmatic threat detection footprints.
* **Multi-Router Topology Configuration**: Built an interconnected multi-network architecture inside Cisco Packet Tracer using a cross-over media infrastructure link, clearing default gateway logic configurations and implementing gold-standard network edge addressing layout protocols (`.1` / `.254` pair assignments across a shared `/24` subnetwork block).

#### 2. Linux Automation Engineering & Background Service (Daemon) Auditing
* **User-Level Scheduled Tasks**: Configured cron time scheduling profiles utilizing explicit 5-position chronological syntax (`* * * * *`) to provision automated background tracking logs (`system_activity.log`).
* **Kernel Automation Debugging**: Remedied functional variable evaluation compilation faults inside the cron schedule configuration by replacing dead text components with legitimate kernel string evaluations (`$(date)` expansion modules).
* **System-Level Service Enumeration**: Queried core background process spaces using `systemctl` architecture to isolate persistent root system daemons (`cron.service`, `snapd.service`, `rtkit-daemon.service`). 
* **Persistence Vector Hardening**: Neutralized a simulated persistent threat actor entry mechanism by executing programmatic containment workflows to kill and permanently deactivate administrative system utilities via system controllers.

#### 3. Python Interactive Gateway & Authentication Logic
* **Dynamic Input Capture**: Implemented user-interactive scripts utilizing the `input()` stream function to capture human string data inputs in real-time.
* **Multi-Factor Logic Verification**: Engineered strict validation barriers leveraging the bitwise logical `and` operator to evaluate compound variable matches simultaneously.
* **Defensive Gateway Simulation**: Built a production-style authentication prompt, incorporating system spacing sequences (`\n` linebreaks) and security alert standards (`[+]` indicator flags) to successfully route application control paths to distinct secure shell or SIEM alerting vectors.
