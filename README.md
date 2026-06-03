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

  ### 🛡️ Day 5: Compound Infrastructure Hardening & Python Logic Blitz

#### 1. Project-Driven Linux Compound Lab
* **Automated Architecture Pipelines**: Constructed a connected multi-tiered security system inside the Ubuntu kernel, linking system logging, automated script execution, and absolute file system configurations.
* **Script Automation Execution**: Authored an operational backup utility script (`backup_system.sh`) using the `nano` editor, designing data cloning pipelines to copy and secure active system audit files (`secure_audit.log`).
* **Absolute Permission Hardening**: Diagnosed and resolved standard kernel-level `Permission denied` execution faults by calculating and applying precise bitwise access modifiers (`chmod 744`) to protect script files from unprivileged modification.
* **Persistent Cron Automation**: Linked the hardened execution script directly to the root operating system clock parameters via `crontab -e`, successfully scheduling background daemons (`crond`) to automatically run system backups every 60 seconds.
* **Diagnostic Timestamp Auditing**: Deployed granular file listing filters (`ls -l --time-style=+%H:%M`) to audit file system metadata and confirm active execution down to the exact minute boundary.

#### 2. Python 5-Problem Loops Blitz & High-Repetition Logic Comprehension
* **Data Iteration Frameworks**: Mastered structural array looping using explicit `for` loop syntax, processing data strings and numeric arrays in sequential CPU execution passes.
* **String Concatenation Mechanics**: Identified and resolved terminal output text quotation constraints by utilizing string concatenation (`+`) to securely weld static text blocks to dynamic variables.
* **Conditional Search Mechanics**: Combined loops with conditional validation barriers (`if`/`else`) to hunt for malicious footprints, identifying a targeted compromised account (`employee1`) out of a live system data stream.
* **State Change Tracking**: Engineered counting algorithms (`counter = counter + 1`) to dynamically track security trends, successfully calculating brute-force login attack frequencies and endpoint compliance violations.
* **Compound Logic Operators**: Deployed bitwise logical `or` evaluations inside automated execution steps to isolate and block network traffic targeting restricted infrastructure ports (SSH 22 / RDP 3389).

  ### 🛡️ Day 6: Routing Foundations, Compound Log Rotators & Advanced Python Loop Matrices

#### 1. Layer 3 Routing Fundamentals & Static Routing (CCNA Day 11)
* **Layer 3 Packet De-Encapsulation**: Mastered the operational sequence of network routers upon packet receipt, analyzing the decapsulation of Layer 2 frame structures to process Layer 3 Destination IP addresses.
* **Routing Table Determinism**: Analyzed router path choices via internal routing tables, utilizing the Longest Match rule algorithm to select optimal next-hop paths.
* **Static Route Implementation Rules**: Studied administrative path configuration protocols using manual static route assertions to hardcode network transit channels, and documented defensive "blackhole routing" logic to discard malicious traffic at the network edge.

#### 2. Project-Driven Linux Compound Lab
* **Automated Architecture Pipelines**: Constructed a connected multi-tiered security system inside the Ubuntu kernel, linking system logging, automated script execution, and absolute file system configurations.
* **Script Automation Execution**: Authored an operational backup utility script (`backup_system.sh`) using the `nano` editor, designing data cloning pipelines to copy and secure active system audit files (`secure_audit.log`).
* **Absolute Permission Hardening**: Diagnosed and resolved standard kernel-level `Permission denied` execution faults by calculating and applying precise bitwise access modifiers (`chmod 744`) to protect script files from unprivileged modification.
* **Persistent Cron Automation**: Linked the hardened execution script directly to the root operating system clock parameters via `crontab -e`, successfully scheduling background daemons (`crond`) to automatically run system backups every 60 seconds.
* **Diagnostic Timestamp Auditing**: Deployed granular file listing filters (`ls -l --time-style=+%H:%M`) to audit file system metadata and confirm active execution down to the exact minute boundary.

#### 3. Python Advanced Boolean Flags & Array Searching Metrics
* **State Preservation Operations**: Engineered global Boolean threat flags (`True`/`False`) inside linear loop passes to preserve network state records across dynamic datasets.
* **Pipeline Early-Termination**: Deployed the loop-interrupt `break` keyword to enforce instant execution kill-switches, optimizing CPU clock cycles by aborting background file scans immediately upon threat verification.
* **Defensive String Normalization**: Implemented case-insensitive input parsing using the `.lower()` method, neutralizing signature bypass tactics where malicious actors obscure payloads using mixed-case characters.
* **Network Whitelist Architectures**: Constructed secure data exclusion perimeters using the logical `not in` membership operator to dynamically match real-time connection traffic against an approved array of safe ports (80/443).
* **Compliance Ratio Computation**: Programmed a system-wide endpoint risk calculator that dynamically computes an infrastructure exposure percentage metric based on data array index parameters.

### 🛡️ Day 7: Routing Fundamentals, Dynamic Archive Engineering & Multi-Stage Bash Pipelines

#### 1. Layer 3 Routing Fundamentals (CCNA Day 11 & 12 Tracking)
* **Layer 3 Packet De-Encapsulation**: Mastered the operational sequence of network routers upon packet receipt, tracking the destruction of Layer 2 frame wrappers to evaluate Layer 3 Destination IP configurations.
* **Routing Table Determination**: Analyzed internal routing table lookup paths, documenting how the router utilizes the Longest Match rule algorithm to parse overlapping network metrics and select the optimal next-hop interface link.

#### 2. Project-Driven Linux Compound Lab (Log Rotator Phase 2 & Web Segregator)
* **Dynamic Variable Encapsulation**: Upgraded custom shell scripts by encapsulating live hardware clock variables (`NOW=$(date +%Y-%m-%d_%H-%M)`), forcing the kernel to dynamically generate unique historical file paths.
* **Troubleshooting and Path De-Duplication**: Diagnosed and resolved classic file system compilation bugs including multi-nested path errors (`/home/seckitty/home/seckitty/` duplicates) and structural tilde path scattering parameters.
* **Automated Data Compression Pipelines**: Engineered two complete, production-tier shell utilities (`log_rotator.sh` and `web_segregator.sh`), successfully implementing high-performance archiving algorithms (`tar -czf`) to compress text strings into timestamped `.tar.gz` containers before cleanly purging raw logs via `rm`.
* **Least Privilege Parameter Hardening**: Enforced absolute numerical access perimeters (`chmod 744`), validating execution permissions for the script owner while maintaining strict read-only barriers across external group domains.

### 🛡️ Day 8: Network Socket Auditing & Conditional Loops (While-Loop Foundations)

#### 1. Project-Driven Linux LAN & Network Audit Project
* **Hardware Interface Profiling**: Utilized the Linux kernel parameters (`ip -4 addr show`) to identify the local network interface properties (`enp0s3`) and map active IPv4 and CIDR configurations (`10.0.2.15/24`).
* **Automated Auditing Engines**: Authored an integrated network profile script (`lan_scanner.sh`) to query live routing metrics and default network gateway exits (`ip route show`).
* **Diagnostic Pipeline Correction**: Troubleshooted shell compilation bugs by replacing mismatched address discovery commands with explicit routing lookup tables and tracking loopback behaviors (`10.0.2.2`).
* **Active Port Stream Enumeration**: Applied socket streaming tools (`ss -tulpn`) inside multi-tiered automation pipelines to dump open network listeners straight into timestamped log containers.

#### 2. Python Loop Control Mechanisms & Variable Interrogation Blitz
* **Conditional Logic Loops**: Mastered the execution bounds of `while` loops, tracking state variations in CPU registers to verify when specific conditions evaluate to False.
* **Authentication Gateways**: Engineered secure system lockout screens, combining iteration limit thresholds with structural break parameters to terminate loop executions upon valid input matches.
* **Dynamic Array Shrinkage**: Deployed array popping tools (`pop(0)`) to modify queue sizes in system memory dynamically, systematically cleaning a SIEM incident array down to a size metric of zero.
* **Interactive Shell Emulation**: Built an operational incident response command prompt interface utilizing Boolean driver flags (`session_active = True`) to process user inputs and handle continuous workflow cycles.



