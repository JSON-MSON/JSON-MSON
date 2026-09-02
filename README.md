### I'm Jason

Aspiring cybersecurity analyst with hands-on experience across SIEM detection engineering, identity and access management, incident response, and security control framework mapping — backed by a **Google Cybersecurity Professional Certificate** and **CompTIA Security+** (in progress). I built a home lab from scratch — isolated VM infrastructure, attack simulation, defensive tooling, and identity administration — and documented all of it here.

Before this, I spent 20+ years in high-stakes, self-managed operational roles (CDL freight logistics with a perfect FMCSA compliance record, and two decades as an executive chef) — the same discipline around documentation, regulatory adherence, and independent decision-making now applied to IT/security work.

---

### 🧪 Home Lab Projects

| Project | What it demonstrates |
|---|---|
| [`packet-analysis-lab`](https://github.com/JSON-MSON/packet-analysis-lab) | Network traffic capture and analysis with Wireshark/tshark — port scan detection, encrypted vs. plaintext credential exposure, and a measured firewall-hardening pass (5 → 2 open ports, verified via a full 65535-port scan) |
| [`siem-home-lab`](https://github.com/JSON-MSON/siem-home-lab) | Self-hosted Wazuh SIEM deployment with two custom MITRE ATT&CK-mapped detection rules — SSH brute-force (T1110) and privilege escalation (T1548) — each validated against live attack traffic, mapped onto a MITRE ATT&CK Navigator layer covering three confirmed techniques alongside a curated roadmap, and visualized in custom Wazuh dashboard panels built from live alert data |
| [`linux-audit-lab`](https://github.com/JSON-MSON/linux-audit-lab) | Bash-scripted auditing of auth logs and file permissions, with before/after remediation and continuous drift detection via a scheduled cron job |
| [`log-ioc-parser`](https://github.com/JSON-MSON/log-ioc-parser) | Python script parsing auth logs to extract and flag IOCs (IPs behind brute-force attempts), with a structured JSON output mode for downstream tooling, plus a real phishing-email header analysis verifying SPF/DKIM/DMARC alignment |
| [`iam-ad-lab`](https://github.com/JSON-MSON/iam-ad-lab) | Self-hosted Active Directory domain (Samba4) — OU structure, group-based delegation, least-privilege access verified at the ACL level, CSV-driven bulk provisioning, and a verified domain password policy — extended with AD account lockout correlated against live SIEM detection, a tested backup/disaster-recovery process, real endpoint management via RMM (Action1), and a documented risk-acceptance decision to preserve network segmentation over monitoring coverage |
| [`dashboards`](https://github.com/JSON-MSON/dashboards) | Cross-project reporting and framework mapping — a normalized findings dashboard aggregating real evidence from all five other projects, a full attack timeline (recon through remediation) with a measured ~4.4 second Mean Time to Detect, and a NIST CSF 2.0 coverage mapping scoring real artifacts across all six functions (Govern, Identify, Protect, Detect, Respond, Recover) |
| [`incident-reports`](https://github.com/JSON-MSON/incident-reports) | Formal NIST SP 800-61 incident response reports — full investigations covering timeline reconstruction, MITRE ATT&CK mapping, severity/escalation reasoning, and root-cause analysis, built from real hands-on exercises rather than hypothetical scenarios |

---

### 🛠️ Tools & Technologies

**Security & Analysis:** Wireshark · tshark · tcpdump · Nmap · Hydra · Wazuh · OpenSearch Dashboards · Chronicle SIEM · Windows Defender Firewall (PowerShell rule management) · ufw · ss (socket/port analysis) · MITRE ATT&CK Navigator
**Identity & Access:** Active Directory Domain Services (Samba4) · samba-tool CLI administration · SDDL/ACL-based delegation · winbind/PAM/NSS (Linux-to-AD integration)
**Frameworks:** NIST SP 800-61 (Incident Handling) · NIST CSF 2.0 · MITRE ATT&CK
**Endpoint Management:** Action1 (RMM)
**Systems:** Windows 10/11 · macOS · Linux (Ubuntu, Kali, Debian)
**Virtualization:** VMware Fusion · Boot Camp
**Reporting:** Google Sheets
**Scripting:** PowerShell · Bash · Python

---

### 📫 Let's connect

[LinkedIn](https://www.linkedin.com/in/j-mason-7013428b) · Open to remote GRC (Governance, Risk, and Compliance) / Compliance Analyst and Tier 1 SOC Analyst roles
