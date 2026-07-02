# Hi, I'm Rajshree 👋

**Aspiring Cybersecurity Professional.** I build cloud labs, write KQL detections, and ship Python tooling to cut triage time. Coming from an offensive security background (CPTC), I'm now focused on the blue team side — security operations, threat intel, and vulnerability management.

---

### 🧰 Tools & Tech

**SIEM / Detection:** Microsoft Sentinel · KQL · MITRE ATT&CK · Log Analytics
**Cloud & Infra:** Azure · Defender · Linux · Windows Event Logs
**Offensive (for context):** Nmap · Burp Suite · Metasploit · Wireshark
**Languages:** Python · Bash · PowerShell · SQL
**Workflow:** ServiceNow · Git · Markdown reporting

---

### 🔭 Currently building

**[ioc-triage](https://github.com/rajkive/ioc-triage)** — Python CLI that pulls IOCs from Azure Sentinel captures and generates structured threat reports per source IP. Goal: reduce repetitive analyst review time on Tier-1 triage.

---

### 📌 Projects

#### 🛡 [Azure Honeypot + Sentinel SIEM](https://github.com/rajkive/Azure-cloud-lab-telemetry-monitorring---honeypot)
Internet-facing honeypot in Azure feeding Microsoft Sentinel in real time. Authored KQL detection rules tuned on **60,000+ real-world authentication attempts** — including brute-force, geo-anomaly, and credential-spray patterns.
`Azure` `Sentinel` `KQL` `Detection Engineering` `Threat Hunting`

#### 🔍 [IOC Triage Tool](https://github.com/rajkive/ioc-triage)
Python CLI that ingests Sentinel log exports, extracts indicators of compromise, enriches IPs, and outputs a clean threat report. Built around a real SOC workflow.
`Python` `Threat Intel` `SOC Automation`

#### 🪤 [SSH Brute-Force Detector](https://github.com/rajkive/ssh-bruteforce-detector)
Lightweight log parser flagging brute-force patterns in Linux and Windows auth logs. A study in writing detections from raw telemetry without a SIEM.
`Python` `Log Analysis` `Detection`

#### ⌨ [Python Keylogger — Detection R&D](https://github.com/rajkive/py-key-logger)
A minimal keylogger built to understand what endpoint telemetry catches during credential theft. Used as a reference when writing detection rules for adversary behavior.
`Python` `Adversary Emulation` `EDR Concepts`

---

### ✍️ Writeups

I publish walkthroughs, lab notes, and detection write-ups at **[rajkive.github.io](https://rajkive.github.io)**.
