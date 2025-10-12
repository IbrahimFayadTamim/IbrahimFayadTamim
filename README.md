## Hi there 👋

# 🛡️ ITECH1502 Final Project – Let'sDefend Phishing Email Investigation

**Student Name:** Ibrahim Fayad Tamim  
**Student ID:** 30479946  
**Email:** itamim@students.federation.edu.au  
**Unit:** ITECH1502 — Cybersecurity Fundamentals  
**Platform Used:** Let'sDefend (registered with FedUni email)  
**Date:** 13 October 2025  

---

## 📘 Project Overview
This project was completed on the **Let'sDefend** blue-team simulation platform as part of the ITECH1502 Cybersecurity Fundamentals course.  
The selected scenario, **Phishing Email Investigation**, involved analysing a suspicious email allegedly sent by PayPal in German.  
The task was to determine whether the email was malicious, identify Indicators of Compromise (IoCs), and apply containment actions following real-world SOC (Security Operations Center) procedures.

Through this investigation, I practiced safe analysis of email headers, URLs, and attachments using sandboxing, SIEM and EDR correlation tools provided in Let'sDefend.  
This hands-on exercise demonstrates my ability to identify phishing attacks, analyse malicious indicators, and document results using standard cybersecurity methodologies.

---

## 🎯 Objectives
- Confirm whether the suspicious email was malicious.  
- Identify and document Indicators of Compromise (IoCs).  
- Analyse headers, links, and attachments using sandboxing and reputation tools.  
- Correlate host and network logs in SIEM/EDR modules.  
- Contain and mitigate the incident, documenting all actions.  

---

## 🧠 Skills & Tools Used
- **Let'sDefend Platform:** Email investigation, SIEM, and EDR dashboards.  
- **VirusTotal:** URL and file reputation checks.  
- **urlscan.io:** Visual inspection of phishing URLs.  
- **Sandbox (Let'sDefend):** Behavioural malware analysis.  
- **NIST CSF Framework:** Identify → Protect → Detect → Respond → Recover.  
- **GitHub:** For evidence documentation and portfolio development.  

---

## 🧾 Project Files
| Folder / File | Description |
|----------------|-------------|
| `Final_Project_Report_READY.docx` | Complete report (Word format) |
| `Final_Project_Report_READY.pdf` | Final PDF report for submission |
| `/evidence/` | Screenshots and logs collected during the challenge |
| `README.md` | Project documentation (this file) |
| `/presentation/` *(optional)* | PowerPoint slides for 5-minute presentation |

---

## 📂 Evidence Files
Ensure the following evidence is included in your repository:

| File | Description |
|------|--------------|
| `01_account_screenshot.png` | LetsDefend account page showing FedUni email |
| `02_challenge_page.png` | Phishing challenge overview (PayPal email example) |
| `03_email_raw_headers.txt` | Extracted raw headers from the phishing email |
| `04_attachment_sandbox.png` | Sandbox screenshot showing malicious macro activity |
| `05_virustotal_results.png` | VirusTotal analysis result of link or attachment |
| `06_siem_results.png` | SIEM logs showing process creation & outbound connection |
| `07_completion_screenshot.png` | Proof of challenge completion |

> ⚠️ Before publishing your GitHub repository, remove any personal or sensitive data (e.g., login details or unredacted email addresses).

---

## 📊 Results Summary
| Component | Finding |
|------------|----------|
| **Sender Domain** | Spoofed PayPal address with failed SPF & DKIM |
| **Attachment** | `Invoice_2025.docm` – macro executed PowerShell to download payload |
| **Malicious Link** | Redirected to credential harvesting site |
| **IoCs Identified** | IP: `203.0.113.45`, Domain: `ex-payments.com` |
| **Containment Actions** | Host isolated, credentials reset, malicious IP/domain blocked |

---

## 💡 Reflection
This project improved my understanding of phishing detection and SOC workflows.  
It reinforced practical skills in:
- Analysing email headers and URLs safely.  
- Interpreting sandbox, SIEM, and EDR data.  
- Documenting incident response steps using real-world frameworks.  

I also learned the importance of automating repetitive tasks, such as SIEM queries, and capturing forensic images before remediation.

---

## 🎤 Presentation (5-Minute Slide Outline)
1. **Title & Objective** — Overview of the phishing incident investigation.  
2. **Challenge Context** — Description of the PayPal phishing email.  
3. **Investigation Process** — Email header, sandbox, and SIEM/EDR analysis.  
4. **Findings** — Indicators of compromise, malicious IPs/domains.  
5. **Containment & Lessons Learned** — Actions taken and key reflections.  

---

## 🔗 References
- [Let'sDefend Platform](https://letsdefend.io)  
- [VirusTotal](https://www.virustotal.com)  
- [urlscan.io](https://urlscan.io)  
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)  

---

## ✅ Submission Notes
- The **PDF report** should be uploaded to Moodle as  
  `Tamim 30479946 FinalProject_Report.pdf`  
- The **GitHub repository** should be set to *Public* for academic verification.  
- Ensure all screenshots clearly show your **FedUni email** for authenticity.  

---

### © 2025 — Ibrahim Fayad Tamim  
Federation University Australia  
ITECH1502 — Cybersecurity Fundamentals

<!--
**IbrahimFayadTamim/IbrahimFayadTamim** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
