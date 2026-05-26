# 100-Days-Cybersecurity-Sprint
Objective: Transitioning into an enterprise Tier-1 SOC Analyst role within 100 days.
Daily Commitment: 11 Hours of structured technical infrastructure study, defensive hands-on lab simulations, and Python/AI automation development.
Target Location: Chennai / Bengaluru Tech Hubs (MSSPs & Consultancies).
---

## 📅 Daily Execution Tracking

### 🛡️ Day 1 & Day 2: Network Infrastructure & Systems Architecture Foundations

#### 1. Core Networking Architecture (CCNA Modules 1-6)
* **OSI vs. Modern TCP/IP Models**: Mastered the 5-Layer conceptual framework and protocol data units (PDUs). Documented structural encapsulation transformations: Data (L5) ➔ Segment (L4) ➔ Packet (L3) ➔ Frame (L2) ➔ Bits (L1) [1].
* **Layer 2 Data Link Switching Logic**: Analyzed how a hardware switch utilizes incoming frame source MAC addresses to populate its CAM/MAC address table dynamically while leveraging destination MAC addresses to execute precise filtering, forwarding, or flooding operations [1].
* **Micro-Segmentation & Collision Domains**: Audited the structural shift from Half-Duplex shared collision domains (legacy hubs operating with CSMA/CD mechanisms) to isolated Full-Duplex micro-segments on modern switches, rendering data collisions impossible [1].
* **Cisco IOS CLI Privilege Ladder**: Documented command hierarchy navigation rules across User EXEC (`Switch>`), Privileged EXEC (`Switch#` via `enable`), and Global Configuration (`Switch(config)#` via `configure terminal`) [1].

#### 💻 2. Practical Lab Simulation & Systems Auditing
* **Live Network Discovery Simulation**: Provisioned a 3-node localized star topology connected to a Cisco 2960 Switch inside Cisco Packet Tracer. Switched to simulation frame analytics to observe an ARP Broadcast query (`FF:FF:FF:FF:FF:FF`) trigger a systematic switch-port flooding event [1].
* **CAM Memory Validation**: Formally audited the switch's internal RAM configuration via the CLI utilizing `show mac address-table` to verify dynamic MAC-to-Interface matching parameters [1].
* **Linux Kernel Socket Enumeration**: Logged directly into the Ubuntu sandbox kernel terminal to execute `ss -tulpn` and deployed `nmap 127.0.0.1` to track system exposures, isolating background system operations actively running on Layer 4 security channels (Port 53 DNS / Port 631 Printing Daemon) [1].
