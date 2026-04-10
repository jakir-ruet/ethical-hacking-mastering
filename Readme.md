## More About Me – [Take a Look!](http://www.mjakaria.me)

## Overview

This series of courses and hands-on labs provides comprehensive preparation for the EC-Council® C|EH® (Certified Ethical Hacker) certification. It covers all the essential topics and skills required for both the `312-50 (ECC EXAM)` and `312-50 (VUE)` exam formats, helping learners gain practical experience and exam readiness.

### Ethical Hacking (white-hat hacking)

Ethical hacking is the `legal` and `authorized` practice of `testing computer systems`, `networks`, or `applications` to find and `fix security vulnerabilities` before they can be exploited by malicious attackers. In a word `Ethical hacking means hacking with permission to improve security.`

> **Key Points**

- Done with permission from the owner
- Aims to identify weaknesses in systems
- Helps protect data and prevent cyber attacks
- Follows legal and ethical guidelines

**Necessary Courses**

Let me break it down clearly so you don’t waste time or money.

1. [Certified Ethical Hacker - Beginner](https://github.com/jakir-ruet/ethical-acking-mastering/tree/master/01-ceh), [More](https://www.eccouncil.org/train-certify/certified-ethical-hacker-ceh/)
2. [Cybrary Ethical Hacking - Intermediate](https://github.com/jakir-ruet/ethical-acking-mastering/tree/master/02-ceh), [More](https://www.cybrary.it/certification-prep-courses/penetration-testing-and-ethical-hacking)
3. [Penetration Testing with Kali - Advanced](https://github.com/jakir-ruet/ethical-acking-mastering/tree/master/03-ptk), [More](https://www.offsec.com/courses/pen-200/)
4. [SANS Ethical Hacking Bootcamp - Advanced](https://github.com/jakir-ruet/ethical-acking-mastering/tree/master/04-sans-ceh), [More](https://www.sans.org/mlp/ethical-hacking)

### Understanding Ethical Hacking Series

full Ethical Hacking Series with detailed subcategories for every main topic. I’ve structured it as a comprehensive learning roadmap from Beginner → Advanced

| Level        | Topic                              | Subcategories                                                                                      | What You Learn                                                    |
| ------------ | ---------------------------------- | -------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Beginner     | Introducing Ethical Hacking        | –                                                                                                  | Basics, legality, types of hackers, methodologies                 |
| Beginner     | Reconnaissance / Footprinting      | Website, Whois, DNS, IP mapping, Open ports, Social media                                          | Gathering info about targets, both passive and active methods     |
| Beginner     | Scanning Networks                  | Network scanning, Port scanning, Service detection, OS fingerprinting                              | Finding live systems, open ports, and services                    |
| Beginner     | Enumeration                        | User enumeration, Share enumeration, Service enumeration, SNMP, NetBIOS                            | Extracting detailed information about systems and users           |
| Beginner     | Vulnerability Analysis             | Automated tools, Manual assessment, CVE database, Risk prioritization                              | Identifying system and application weaknesses                     |
| Intermediate | System Hacking                     | Password cracking, Privilege escalation, Backdoors, Rootkits                                       | Gaining access, escalating privileges, maintaining access         |
| Intermediate | Malware Threats                    | Viruses, Worms, Trojans, Ransomware, Spyware, Adware                                               | Understanding malware types, attack vectors, and mitigation       |
| Intermediate | Sniffing                           | Packet capturing, Protocol analysis, MITM attacks, ARP poisoning                                   | Capturing and analyzing network traffic to extract sensitive data |
| Intermediate | Social Engineering                 | Phishing, Pretexting, Baiting, Tailgating, Vishing                                                 | Manipulating humans to gain confidential info or access           |
| Intermediate | Denial of Service (DoS)            | Flood attacks, Botnets, Resource exhaustion, SYN/ACK floods                                        | Disrupting system or network availability                         |
| Intermediate | Session Hijacking                  | Cookie theft, TCP/IP hijacking, Man-in-the-middle, Token theft                                     | Taking control of active sessions for unauthorized access         |
| Intermediate | Evading IDS, Firewalls & Honeypots | IDS evasion, Firewall bypass, Honeypot detection, Packet fragmentation                             | Avoiding detection while performing attacks                       |
| Advanced     | Hacking Web Servers                | Apache, Nginx, IIS, Misconfigurations, Directory traversal                                         | Exploiting server vulnerabilities to gain control or data         |
| Advanced     | Hacking Web Applications           | XSS, CSRF, Authentication bypass, File upload attacks, Remote code execution                       | Identifying and exploiting web app vulnerabilities                |
| Advanced     | SQL Injection                      | Error-based, Blind, Union-based, Time-based, Second-order                                          | Exploiting database query flaws for unauthorized access           |
| Advanced     | Hacking Wireless                   | WEP/WPA/WPA2 cracking, Evil Twin, Rogue AP, Packet injection                                       | Attacking Wi-Fi networks and intercepting traffic                 |
| Advanced     | Hacking Mobile                     | Android app vulnerabilities, iOS app vulnerabilities, Reverse engineering, Jailbreak/root exploits | Testing mobile devices and apps for security issues               |
| Advanced     | IoT & OT Hacking                   | Smart devices, SCADA systems, Industrial protocols, Default credentials                            | Attacking connected devices and operational tech systems          |
| Advanced     | Cloud Computing                    | AWS, Azure, Google Cloud, Misconfigurations, API security, IAM flaws                               | Security in cloud environments and SaaS platforms                 |
| Advanced     | Cryptography                       | Symmetric encryption, Asymmetric encryption, Hashing, Digital signatures, Cryptanalysis            | Protecting data and breaking weak encryption schemes              |

**Some Interesting Statistics**

- Cyberattacks occur continuously around the world.
- New malware is created every day.
- Governments invest heavily in cybersecurity.
- Cybercrime is an extremely profitable global industry.
- Skilled hackers can breach networks very quickly.

### Fundamentals of Information Security

| Principle           | Description                                    | Example                          | Control Mechanisms                          |
| ------------------- | ---------------------------------------------- | -------------------------------- | ------------------------------------------- |
| **Confidentiality** | Protect data from unauthorized access          | Encrypting sensitive files       | Encryption (AES), Access Control (IAM)      |
| **Integrity**       | Ensure data is not altered                     | File hash verification           | Hashing (SHA-256), Digital signatures       |
| **Availability**    | Ensure systems/data are accessible when needed | Website uptime                   | Load balancing, backups, DR                 |
| **Authenticity**    | Verify identity of users/systems               | Login with username/password     | MFA, certificates, authentication protocols |
| **Non-repudiation** | Prevent denial of actions                      | Email sender cannot deny sending | Digital signatures, logging, PKI            |

### Types of Attacks

| Attack Type              | Description                      | Example                          | Mitigation                            |
| ------------------------ | -------------------------------- | -------------------------------- | ------------------------------------- |
| **Passive Attacks**      | Monitor data without altering it | Packet sniffing                  | Encryption (TLS), VPN                 |
| **Active Attacks**       | Modify or disrupt systems        | Man-in-the-middle, DoS           | IDS/IPS, firewalls                    |
| **Insider Attacks**      | Performed by trusted users       | Employee stealing data           | Least privilege, monitoring           |
| **Close-in Attacks**     | Require physical proximity       | Shoulder surfing, Wi-Fi sniffing | Physical security, network encryption |
| **Distribution Attacks** | Tampering during supply chain    | Backdoored hardware/software     | Vendor validation, integrity checks   |

### Attack Formula

`Attacks = Motive + Method + Vulnerability`

| Component         | Meaning              | Example                   |
| ----------------- | -------------------- | ------------------------- |
| **Motive**        | Reason behind attack | Financial gain, espionage |
| **Method**        | Technique used       | Phishing, malware         |
| **Vulnerability** | Weakness exploited   | Unpatched system          |

### Cyber Kill Chain Methodology - `R → W → D → E → I → C → A`

| Phase                      | Description                         | Attacker Activity                        | Example                                  | Defense Strategy                      |
| -------------------------- | ----------------------------------- | ---------------------------------------- | ---------------------------------------- | ------------------------------------- |
| **Reconnaissance**         | Gather information about the target | Scanning, OSINT, social engineering      | Collecting employee emails from LinkedIn | WAF, IDS/IPS, threat intelligence     |
| **Weaponization**          | Create malicious payload            | Combine exploit + malware                | Embedding malware in Word/PDF            | Threat intelligence, malware analysis |
| **Delivery**               | Send payload to victim              | Phishing email, USB, malicious link      | Email with infected attachment           | Email filtering, sandboxing           |
| **Exploitation**           | Execute the attack                  | Trigger vulnerability                    | User opens malicious file                | Patch management, EDR                 |
| **Installation**           | Establish persistence               | Install malware/backdoor                 | Registry changes, scheduled tasks        | Application control, EDR              |
| **Command & Control (C2)** | Connect to attacker server          | Remote control communication             | Malware connects to C2 server            | Network monitoring, DNS filtering     |
| **Action on Objectives**   | Achieve attack goal                 | Data theft, ransomware, lateral movement | Exfiltration of database                 | DLP, SIEM, Zero Trust                 |

> - **Reconnaissance:** Is the preliminary survey, exploration, or inspection of an area to gather information about enemy forces, terrain, or resources.
> - **Weaponization**: Is the process of adapting a substance, object, or concept into a tool for causing harm, inflicting injury, or gaining a tactical advantage.
> - **Exploitation:** Is the unfair, manipulative use of a person or resource for personal advantage, often involving coercion, abuse of power, or taking advantage of vulnerability.

### Tactics, Techniques, and Procedures (TTPs)

| Component      | Description                               | Focus Area                    | Example                                            | Detection / Defense                |
| -------------- | ----------------------------------------- | ----------------------------- | -------------------------------------------------- | ---------------------------------- |
| **Tactics**    | High-level goal of the attacker           | *Why* the attack is happening | Initial Access, Persistence, Data Exfiltration     | Security strategy, threat modeling |
| **Techniques** | Methods used to achieve the tactic        | *How* the attack is done      | Phishing, Exploiting vulnerabilities               | IDS/IPS, EDR, SIEM                 |
| **Procedures** | Step-by-step implementation of techniques | *Exactly how* it is executed  | Sending crafted phishing email with malicious link | Threat hunting, behavior analysis  |

### Adversary (Oponent) Behavioral Identification

Its the process of detecting and analyzing malicious actors by observing their patterns of behavior, actions, and techniques within a system or network, rather than relying solely on known signatures or indicators.

| Behavior                              | Description                                                 | Indicators (What to Look For)                                       | Example                                     | Detection / Mitigation                                     | MITRE ATT&CK     |
| ------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------- | ---------------------------------------------------------- | ---------------- |
| **Internal Reconnaissance**           | Attacker discovers internal assets after initial compromise | Network scans, LDAP queries, account & host enumeration             | Compromised user scanning subnet            | NDR, IDS/IPS, Zero Trust, AD monitoring                    | T1087, T1018     |
| **Suspicious Proxy Events**           | Abnormal outbound traffic via proxy infrastructure          | Rare domains, unusual bandwidth, policy bypass attempts             | User accessing unknown or risky domains     | Proxy log analysis, URL filtering, CASB                    | T1071            |
| **PowerShell Abuse**                  | Malicious use of PowerShell for execution or persistence    | Encoded commands, remote script execution, obfuscation              | Base64-encoded PowerShell payload           | EDR, PowerShell logging, AMSI, script control              | T1059.001        |
| **HTTP User-Agent Anomalies**         | Use of fake or non-standard client identifiers              | Uncommon agents, mismatched browser behavior                        | `curl/7.68.0`, scripted malware agent       | WAF, web log analysis, anomaly detection                   | T1071.001        |
| **CLI Processes**                     | Suspicious command-line activity using native tools         | Abnormal admin commands, privilege escalation attempts              | `whoami`, `net user`, `ipconfig` misuse     | Endpoint monitoring, audit logs, EDR                       | T1059            |
| **Command & Control (C2)**            | Communication with attacker-controlled infrastructure       | Beaconing patterns, repeated outbound traffic, unknown destinations | Periodic connection to suspicious IP/domain | DNS filtering, NDR, firewall rules, threat intel           | T1071, T1095     |
| **Data Exfiltration (DNS Tunneling)** | Stealthy data transfer using trusted protocols like DNS     | High DNS query volume, long/random subdomains, encoded payloads     | `data.exfil.attacker.com`                   | DNS monitoring, DLP, anomaly detection, DNS security tools | T1048, T1071.004 |

### Indicators of Compromise (IoC)

Indicators of Compromise (IoCs) are observable signs or evidence that a system or network may have been breached or is under attack. Some common IoCs mention below table

| Category             | IoC                             | What It Means                            |
| -------------------- | ------------------------------- | ---------------------------------------- |
| **Files & Software** | Unauthorized software/files     | Malware, backdoors, unknown binaries     |
| **Email**            | Suspicious emails               | Phishing, malicious attachments/links    |
| **System Changes**   | Registry & file system changes  | Persistence mechanisms, malware activity |
| **Network**          | Unknown ports/protocols         | Backdoors, covert communication          |
| **Bandwidth**        | Excessive usage                 | Possible data exfiltration               |
| **Hardware**         | Rogue devices                   | Unauthorized USB, network devices        |
| **Availability**     | Service disruption / defacement | DoS or web compromise                    |
| **Identity**         | Unauthorized account usage      | Account takeover, privilege abuse        |

### `IoCs` vs `Behavioral` Detection

| Aspect              | **IoCs (Indicators of Compromise)**                        | **Behavioral Detection (Adversary Behavior)**       |
| ------------------- | ---------------------------------------------------------- | --------------------------------------------------- |
| **Definition**      | Observable evidence that a system **has been compromised** | Detection based on **patterns of attacker actions** |
| **Focus**           | **What happened (evidence)**                               | **How it happened (behavior/pattern)**              |
| **Nature**          | Static (IP, hash, file, domain)                            | Dynamic (activities, sequences, patterns)           |
| **Detection Type**  | Signature-based                                            | Behavior / anomaly-based                            |
| **Effectiveness**   | Good for **known threats**                                 | Effective for **unknown / zero-day attacks**        |
| **Evasion Risk**    | Easy to evade (change IP, hash)                            | Harder to evade (behavior is consistent)            |
| **Examples**        | Malicious IP, file hash, suspicious domain                 | Reconnaissance, lateral movement, C2 communication  |
| **Tools Used**      | Antivirus, IOC feeds, threat intel                         | EDR, SIEM, UEBA                                     |
| **Response Speed**  | Fast for known attacks                                     | May require correlation and analysis                |
| **False Positives** | Lower (specific indicators)                                | Higher (needs tuning)                               |

#### EDR vs SIEM vs UEBA

| Tool     | Full Form                                 | Purpose                                                          | Focus                       | Data Source                                 | Strength                                 |
| -------- | ----------------------------------------- | ---------------------------------------------------------------- | --------------------------- | ------------------------------------------- | ---------------------------------------- |
| **EDR**  | Endpoint Detection & Response             | Detect and respond to threats on endpoints (laptops, servers)    | Endpoint activity           | Process, file, registry, memory logs        | Deep visibility on host attacks          |
| **SIEM** | Security Information and Event Management | Collect, correlate, and analyze logs from all systems            | Centralized log correlation | Network, server, apps, firewall, cloud logs | Enterprise-wide visibility               |
| **UEBA** | User and Entity Behavior Analytics        | Detect abnormal behavior of users and systems using analytics/AI | Behavioral anomalies        | User login patterns, access behavior        | Detect insider threats & unknown attacks |

### Diamond Model of Intrusion Analysis

The Diamond Model was developed by Center for Cyber Intelligence Analysis and Threat Research. It helps analysts understand cyber intrusions by linking four core elements.

| Component          | Description                     | Key Question                     | Example                  |
| ------------------ | ------------------------------- | -------------------------------- | ------------------------ |
| **Adversary**      | The attacker or threat actor    | Who is attacking?                | Hacker group, insider    |
| **Capability**     | Tools, malware, techniques used | How is the attack performed?     | Malware, exploit kits    |
| **Infrastructure** | Systems used to launch attack   | Where does the attack come from? | C2 servers, domains, IPs |
| **Victim**         | Target of the attack            | Who is being attacked?           | Organization, user       |

### Hacking Concepts

`Hacking is exploiting security controls either in a technical, physical or a human-based element` by `Kevin Mitnick`

#### Three areas of exploitation

##### 1. Technical exploitation

Attacking software, hardware, or network vulnerabilities, like

- `Buffer overflows`– injecting malicious code into memory.
- `SQL injection` – manipulating database queries.
- `Exploiting` unpatched vulnerabilities (e.g., EternalBlue).

> **Why it works:** Software is complex, and bugs are inevitable.

##### 2 Physical exploitation

Bypassing physical barriers to access systems or data, like:

- `Tailgating` – following an authorized person through a secure door.
- `Dumpster diving` – retrieving discarded documents or devices.
- `Lock picking` or bypassing badge readers.

> **Why it works:** Physical security is often overlooked or poorly enforced.

##### 3. Human-based exploitation (Social Engineering)

Manipulating people into revealing information or performing actions, like

- `Phishing` – fake emails tricking users into clicking malicious links.
- `Pretexting` – inventing a scenario to extract data (e.g., calling IT support for a password reset).
- `Baiting` – leaving an infected USB drive in a parking lot.

> **Why it works:** Humans are often the weakest link due to trust, helpfulness, or lack of awareness.

**Summary**

| Layer     | Controls Needed                                 |
| --------- | ----------------------------------------------- |
| Technical | Firewalls, IAM, encryption, patching            |
| Physical  | CCTV, access control, biometric locks           |
| Human     | Security awareness, phishing training, policies |

#### Types of Hackers

| Type                  | Description                                         | Motivation                          | Skill Level                    | Example                                                   |
| --------------------- | --------------------------------------------------- | ----------------------------------- | ------------------------------ | --------------------------------------------------------- |
| **Black Hat Hackers** | Malicious hackers who exploit systems illegally     | Financial gain, revenge, cybercrime | High to advanced               | Ransomware attackers stealing data                        |
| **White Hat Hackers** | Ethical hackers who test and secure systems legally | Security improvement                | High (certified professionals) | Penetration testers, bug bounty hunters                   |
| **Gray Hat Hackers**  | Operate between legal and illegal boundaries        | Curiosity, reputation               | Medium to high                 | Access system without permission but report vulnerability |
| **Suicide Hackers**   | Attack without concern for consequences             | Ideology, revenge                   | Varies                         | Hackers exposing systems publicly without hiding identity |
| **Script Kiddies**    | Use pre-made tools without deep knowledge           | Fun, curiosity                      | Low                            | Running downloaded hacking tools                          |

#### Types of Cyber Threat Actors

| Threat Actor Type                          | Description                                                               | Motivation                                | Characteristics                                     | Example                      |
| ------------------------------------------ | ------------------------------------------------------------------------- | ----------------------------------------- | --------------------------------------------------- | ---------------------------- |
| **Spy / Cyber Spy**                        | Individuals or groups conducting espionage to steal sensitive information | Intelligence gathering, corporate secrets | Stealthy, long-term access, avoids detection        | Corporate espionage attacker |
| **Cyber Criminals / Organized Crime**      | Groups focused on financial gain through cyber attacks                    | Money (ransomware, fraud, data theft)     | Highly structured, uses malware-as-a-service        | Ransomware gangs             |
| **State-Sponsored Actors**                 | Advanced groups backed by governments                                     | Political, military, strategic advantage  | Highly skilled, well-funded, persistent (APT-level) | Nation-state APT groups      |
| **Hacktivists (Political/Religious)**      | Attackers driven by ideology                                              | Political or religious beliefs            | Defacement, DDoS, data leaks                        | Ideology-driven groups       |
| **Terrorist / Extremist Actors**           | Use cyber attacks to spread fear or disrupt systems                       | Fear, disruption, propaganda              | Targets critical infrastructure                     | Cyber-terror campaigns       |
| **Insider Threats** *(important addition)* | Employees or trusted users misusing access                                | Financial gain, revenge, coercion         | Hard to detect, already inside perimeter            | Disgruntled employee         |

## With Regards, `Jakir`

[![LinkedIn][linkedin-shield-jakir]][linkedin-url-jakir]
[![Facebook-Page][facebook-shield-jakir]][facebook-url-jakir]
[![Youtube][youtube-shield-jakir]][youtube-url-jakir]

### Wishing you a wonderful day! Keep in touch

<!-- Personal profile -->

[linkedin-shield-jakir]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url-jakir]: https://www.linkedin.com/in/jakir-ruet/
[facebook-shield-jakir]: https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white
[facebook-url-jakir]: https://www.facebook.com/jakir.ruet/
[youtube-shield-jakir]: https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white
[youtube-url-jakir]: https://www.youtube.com/@mjakaria-ruet/featured
