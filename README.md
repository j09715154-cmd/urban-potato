# urban-potato
Linux SIEM-style SOC and Incident Response lab using Bash, journalctl, SSH log analysis, and automated firewall containment.
## Linux SIEM & Incident Response Lab (SOC-Focused)

This project demonstrates hands-on **SOC Analyst** and **Incident Response** skills by building a lightweight **SIEM-style detection and response pipeline** on Linux. It focuses on **log analysis, threat detection, SSH brute-force monitoring, credential abuse detection, and automated containment**, using Bash and native Linux tools
# 👋 Hi, I’m Jarvis

🛡️ **SOC / Blue Team | Linux Security | Incident Response**  
🔍 Focused on detection engineering, threat hunting, and low-resource security operations

---

## 🧠 About Me
I’m a hands-on security practitioner building **real detection and incident response workflows** from first principles.  
My work focuses on understanding how SIEMs, EDRs, and SOC pipelines actually work under the hood — not just clicking dashboards.

I enjoy:
- Breaking attacks into signals
- Turning logs into detections
- Automating response and containment
- Building labs that mirror real SOC environments

---

## 🔐 Core Skills
- Linux Security & Hardening
- SSH Attack Detection & Response
- Log Analysis (journalctl, auth.log, auditd)
- Bash Detection Engineering
- Incident Response & Containment
- Threat Hunting
- MITRE ATT&CK Mapping
- Firewall Automation (UFW)

---

## 🚨 Featured Project

### 🧠 Linux Micro-SIEM & Incident Response Lab
🔗 **Repo:** https://github.com/urban-potato/linux-micro-siem-ir-lab

**What it does:**
- Detects SSH brute-force attacks
- Correlates successful logins after brute force
- Automatically blocks attacker IPs
- Detects post-compromise behavior:
  - Privilege escalation
  - New user creation
  - Payload downloads (curl / wget)
- Generates incident timelines and reports

**Why it matters:**
This lab replicates **SOC + IR workflows** using only native Linux tools and Bash — designed for low-RAM environments and deep understanding.

---
---

## 🧬 MITRE ATT&CK Experience
- T1110 – Brute Force
- T1078 – Valid Accounts
- T1548 – Privilege Escalation
- T1105 – Ingress Tool Transfer
- T1136 – Account Creation

---

## 📜 Certifications (In Progress)
- CompTIA A+
- Network+
- Security+

---

## 🛠️ Tools I Work With
- Bash
- journalctl
- OpenSSH
- UFW
- auditd
- cron
- Git & GitHub
- Linux Mint / Ubuntu

---

## 🎯 Goals
- SOC Analyst (Tier 1 → Tier 2)
- Detection Engineering
- Incident Response
- Blue Team Operations

---

## 📫 Connect
- GitHub: https://github.com/urban_potato

## 🖥️ Live SOC Lab Evidence

This project was executed on a real Linux system with continuous monitoring enabled via cron.

**Demonstrated capabilities:**
- Real-time SSH brute-force detection
- Automated firewall containment
- Post-compromise activity detection
- Incident timeline reconstruction
- Ongoing scheduled monitoring

Screenshots and logs included in repository for verification.
