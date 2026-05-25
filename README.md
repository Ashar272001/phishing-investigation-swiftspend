# 🛡️ Phishing Investigation – SwiftSpend Financial

## 📌 Overview
This project documents a phishing investigation conducted in a simulated enterprise environment provided through TryHackMe.

As a member of the IT department at SwiftSpend Financial, multiple employees reported receiving suspicious emails. Several users submitted their credentials, leading to potential account compromise.

The objective of this investigation was to analyze phishing emails, identify indicators of compromise (IOCs), investigate attacker infrastructure, and examine the phishing kit used during the attack.

---

# 🎯 Objectives

- Analyze phishing email samples
- Identify malicious sender infrastructure
- Investigate phishing URLs and redirections
- Retrieve and analyze the phishing kit
- Gather cyber threat intelligence (CTI)
- Identify compromised credentials
- Extract indicators of compromise (IOCs)

---

# 🧰 Tools Used

| Tool | Purpose |
|---|---|
| VirusTotal | Threat intelligence analysis |
| CyberChef | Decoding & data analysis |
| Linux CLI | File investigation |
| sha256sum | File hashing |
| PHP Source Analysis | Phishing kit investigation |

---

# 📧 Initial Phishing Email Analysis

The investigation began by reviewing suspicious emails reported by employees across multiple departments at SwiftSpend Financial.

Analysis of the messages revealed multiple phishing indicators commonly associated with credential harvesting campaigns.

## 🚩 Identified Indicators

- Suspicious sender domain
- External sender warning
- Malicious attachment
- Credential harvesting infrastructure
- Microsoft impersonation

## 📨 Sender Information

| Field | Value |
|---|---|
| Sender | Accounts.Payable@groupmarketingonline.icu |
| Domain | groupmarketingonline.icu |
| Impersonated Brand | Microsoft 365 |


# 📸 Investigation Screenshots

## 📧 Initial Phishing Email
![Phishing Email](screenshots/phishing-email-analysis.png)

---

## 📨 Additional Phishing Email
![Additional Email](screenshots/additional-phishing-email.png)

---

## 🎭 Fake Microsoft Login Portal
![Fake Microsoft Login](screenshots/fake-microsoft-login.png)

---

## 🌐 Exposed Directory Listing
![Exposed Directory](screenshots/exposed-data-directory.png)

---

## 🔐 SHA256 File Hashing
![SHA256 Hashing](screenshots/sha256-hashing.png)

---

## 📂 Exposed Credential Log Directory
![Credential Log Directory](screenshots/credential-log-directory.png)

---

## 🧬 Credential Exfiltration Evidence
![Credential Exfiltration](screenshots/credential-exfiltration-email.png)


---
# ✅ Investigation Outcome

The phishing campaign successfully impersonated Microsoft 365 services to harvest enterprise credentials from SwiftSpend Financial employees.

Through investigation and phishing kit analysis, multiple indicators of compromise (IOCs) were identified, including:

- Malicious sender infrastructure
- Credential harvesting domains
- Exposed phishing kit archives
- Victim credential logs
- Attacker-controlled exfiltration email addresses

The investigation demonstrated practical blue-team skills involving:
- Phishing analysis
- Threat intelligence
- Incident response
- Linux-based investigations
- Credential harvesting analysis
- PHP source code inspection

---

# 📚 Skills Demonstrated

- Email Threat Analysis
- IOC Extraction
- Threat Intelligence Investigation
- SHA256 File Hashing
- Linux CLI Investigation
- Credential Harvesting Detection
- PHP Phishing Kit Analysis
- Security Documentation

---

# 🔗 References

- TryHackMe
- VirusTotal
- CyberChef
