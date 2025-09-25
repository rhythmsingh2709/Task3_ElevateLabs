# Elevate-labs-task-3
Perform a Basic Vulnerability Scan on Your PC
# 🔍 Vulnerability Scan Task - Cybersecurity Internship

## 📌 Task Objective
To perform a basic vulnerability scan on my personal computer using a free vulnerability scanning tool (Nessus Essentials or OpenVAS) and identify any existing security issues.

---

## 🛠 Tool Used
**Nessus Essentials**  
(Nessus Essentials was chosen for its beginner-friendly interface and powerful scanning capabilities.)

---

## 💻 Scan Setup

- **Target:** My local machine (`127.0.0.1`)
- **Scan Type:** Basic Network Scan
- **Scan Duration:** ~18 minutes

---

## 📊 Summary of Findings


| Metric                    | Value              |
|---------------------------|--------------------|
| Scan Name                 | LAN Vulnerability Scan |
| Plugin Feed Version       | 202505290308       |
| Scan Duration             | 18 minutes         |
| Hosts Scanned             | 3 (Local and LAN)  |
| Critical Vulnerabilities  | 1                  |
| High Vulnerabilities      | 4                  |
| Medium Vulnerabilities    | 2                  |
| Info / Low                | Many (74+ info)    |


## ⚠️ Critical & High Vulnerabilities Found

### 1. 🛑 Node.js Multiple Vulnerabilities (CVE-2024-21892, CVE-2024-22019, etc.)
- **Severity**: Critical
- **Affected Package**: Node.js v20.11.0
- **Description**: Multiple high-risk vulnerabilities affecting HTTP processing, path traversal, DoS, and crypto timing attacks.
- **Fix**: Upgrade to Node.js `20.11.1` or higher.

---

### 2. 🚨 Tornado Python Library DoS (CVE-2025-47287)
- **Severity**: High
- **Issue**: Logging-based denial-of-service vulnerability in Tornado < 6.5.0.
- **Fix**: Upgrade to Tornado version `6.5.0`.

---

### 3. ⚠️ SSL Certificate Cannot Be Trusted
- **Severity**: Medium
- **Issue**: Self-signed SSL cert used by Nessus web interface.
- **Fix**: Use a certificate from a trusted CA if using publicly.

---

## 🧠 Lessons Learned
- Identified real-world vulnerabilities and learned to assess severity using CVSS scores.
- Understood how outdated packages (Node.js, Tornado) pose significant risks.
- Practiced best practices like updating dependencies and using verified certificates.

---

## 📖 Key Concepts Covered

- Vulnerability scanning basics  
- Using Nessus Essentials  
- Understanding CVSS scores  
- Identifying critical system vulnerabilities  
- Planning basic remediation steps




