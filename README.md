### I'm Jason

Detection engineering, identity administration, incident response, and control framework mapping — built and broken in an isolated home lab, then documented against independent evidence rather than a tool's own success output. Backed by a **Google Cybersecurity Professional Certificate**, with **CompTIA Security+** in progress.

---

### 🧪 Home Lab Projects

| Project | What it demonstrates |
|---|---|
| **Packet Capture & Traffic Analysis**<br>[`packet-analysis-lab`](https://github.com/JSON-MSON/packet-analysis-lab) | Network traffic capture and analysis with tshark — port scan detection, encrypted vs. plaintext credential exposure, and a measured firewall-hardening pass (5 → 2 open ports, verified via a full 65535-port scan) |
| **Home SIEM Lab (Wazuh)**<br>[`siem-home-lab`](https://github.com/JSON-MSON/siem-home-lab) | Self-hosted Wazuh SIEM with two custom detection rules — SSH brute-force (T1110) and privilege escalation (T1548) — each validated against live attack traffic. Extended with a MITRE ATT&CK Navigator layer covering three confirmed techniques plus a curated roadmap, and custom dashboard panels built from live alert data |
| **Linux Log Auditing & Permission Hardening**<br>[`linux-audit-lab`](https://github.com/JSON-MSON/linux-audit-lab) | Bash-scripted auditing of auth logs and file permissions, with before/after remediation and continuous drift detection via a scheduled cron job |
| **Python Log-Parsing / IOC Extraction**<br>[`log-ioc-parser`](https://github.com/JSON-MSON/log-ioc-parser) | Python script parsing auth logs to extract and flag IOCs (IPs behind brute-force attempts), with a structured JSON output mode for downstream tooling, plus a real phishing-email header analysis verifying SPF/DKIM/DMARC alignment |
| **IAM / Active Directory Case Study**<br>[`iam-ad-lab`](https://github.com/JSON-MSON/iam-ad-lab) | Self-hosted Active Directory domain (Samba4) — OU structure, group-based delegation verified at the ACL level, CSV-driven bulk provisioning, and an enforced domain password policy. Extended with AD account lockout correlated against live SIEM detection, a diff-verified backup/restore test, endpoint management via Action1 RMM, and a documented risk-acceptance decision preserving network segmentation |
| **Cross-Project Security Dashboards**<br>[`dashboards`](https://github.com/JSON-MSON/dashboards) | Cross-project reporting and framework mapping — a findings dashboard aggregating real evidence from five lab projects, an attack timeline (recon through remediation) with a measured ~4.4 second Mean Time to Detect, and a NIST CSF 2.0 mapping scoring real artifacts across all six functions (Govern, Identify, Protect, Detect, Respond, Recover) |
| **Incident Response Reports**<br>[`incident-reports`](https://github.com/JSON-MSON/incident-reports) | Formal NIST SP 800-61 incident response reports — full investigations covering timeline reconstruction, MITRE ATT&CK mapping, severity/escalation reasoning, and root-cause analysis, built from real hands-on exercises rather than hypothetical scenarios |

---

### 🛠️ In This Lab

- **Security & Analysis:** tshark · Nmap · Hydra · Wazuh · OpenSearch Dashboards · ufw · ss (socket/port analysis) · MITRE ATT&CK Navigator
- **Identity & Access:** Active Directory Domain Services (Samba4) · samba-tool CLI administration · SDDL/ACL-based delegation · winbind/PAM/NSS (Linux-to-AD integration)
- **Frameworks:** NIST SP 800-61 (Incident Handling) · NIST CSF 2.0 · MITRE ATT&CK
- **Endpoint Management:** Action1 (RMM)
- **Systems:** Windows 10/11 · macOS · Linux (Ubuntu, Kali, Debian)
- **Virtualization:** VMware Fusion
- **Reporting:** Google Sheets
- **Scripting:** PowerShell · Bash · Python

---

### 📫 Let's Connect

[LinkedIn](https://www.linkedin.com/in/j-mason-7013428b) · Open to remote GRC and SOC analyst roles
