# 🔐 SecurityPlus-Incident-Response-Case-Studies

_A structured collection of security incident scenarios aligned with CompTIA Security+ objectives.  
These case studies demonstrate hands-on incident response methodology, threat detection, and security operations practices._

---

# 📘 Incident Response Methodology Used

Each case study follows the standard security lifecycle:

1. Preparation  
2. Detection & Analysis  
3. Containment  
4. Eradication  
5. Recovery  
6. Lessons Learned  

(Aligned with CompTIA Security+ Security Operations domain)

---

## 🚨 Case Study 01 – Phishing Email Attempt

**Domain Alignment:** Threats, Vulnerabilities & Mitigations  
**Category:** Social Engineering  

### 🔍 Incident
User reported a suspicious password reset email.

### ⚠️ Indicators of Compromise (IOCs)
- Spoofed sender address  
- Urgent language  
- Hyperlink to unknown external domain  

### 🧪 Investigation Steps
1. Reviewed email headers  
2. Validated sender domain reputation  
3. Analyzed URL in sandbox  
4. Reviewed account login logs  

### 🛑 Containment
Blocked sender domain at email gateway.

### 🧹 Eradication
Removed email from affected inboxes using admin tools.

### 🔄 Recovery
Confirmed no unauthorized login attempts occurred.

### 📘 Lessons Learned
User awareness training significantly reduces phishing risk.

---

## 🦠 Case Study 02 – Malware Infection

**Domain Alignment:** Security Operations  
**Category:** Endpoint Security  

### 🔍 Incident
Endpoint antivirus detected malicious executable.

### ⚠️ Indicators
- Unknown background process  
- High CPU utilization  
- Suspicious outbound traffic  

### 🧪 Investigation Steps
1. Isolated system from network  
2. Reviewed running processes  
3. Generated file hash  
4. Checked hash against threat intelligence database  

### 🛑 Containment
Disconnected system from network.

### 🧹 Eradication
Removed malicious file and reimaged workstation.

### 🔄 Recovery
Restored user data from clean backup.

### 📘 Lessons Learned
Rapid isolation prevents lateral movement.

---

## 🔐 Case Study 03 – Brute Force Login Attempt

**Domain Alignment:** Identity & Access Management  

### 🔍 Incident
Multiple failed login attempts detected on administrative account.

### ⚠️ Indicators
- 200+ failed login attempts  
- Foreign IP address source  
- Account lockout triggered  

### 🧪 Investigation Steps
1. Reviewed SIEM authentication logs  
2. Analyzed source IP geolocation  
3. Verified account lockout policy  
4. Checked MFA enforcement  

### 🛑 Containment
Blocked malicious IP at firewall.

### 🧹 Eradication
Forced password reset and enforced MFA.

### 🔄 Recovery
Verified no successful unauthorized logins.

### 📘 Lessons Learned
MFA dramatically reduces brute-force effectiveness.

---

## ☁️ Case Study 04 – Public Cloud Storage Exposure

**Domain Alignment:** Security Architecture  

### 🔍 Incident
Sensitive documents accessible via public cloud storage link.

### ⚠️ Indicators
- Public read permissions enabled  
- No authentication required  

### 🧪 Investigation Steps
1. Reviewed bucket ACL settings  
2. Audited IAM permissions  
3. Checked audit logs for file access  
4. Identified exposed data types  

### 🛑 Containment
Disabled public access settings.

### 🧹 Eradication
Restricted access to authorized users only.

### 🔄 Recovery
Performed access review and notified stakeholders.

### 📘 Lessons Learned
Cloud misconfigurations are a leading cause of data breaches.

---

## 🔍 Case Study 05 – Critical Vulnerability Discovered

**Domain Alignment:** Vulnerability Management  

### 🔍 Incident
Quarterly vulnerability scan identified critical RCE vulnerability.

### ⚠️ Indicators
- CVSS score 9.8  
- Known exploit publicly available  

### 🧪 Investigation Steps
1. Validated scan findings  
2. Confirmed affected systems  
3. Reviewed vendor advisory  
4. Conducted risk assessment  

### 🛑 Containment
Temporarily restricted external access to affected systems.

### 🧹 Eradication
Applied vendor patch.

### 🔄 Recovery
Rescanned system to verify remediation.

### 📘 Lessons Learned
Routine patching significantly reduces exploit risk.

---

## 📡 Case Study 06 – Suspicious Data Exfiltration Attempt

**Domain Alignment:** Security Operations  

### 🔍 Incident
Unusual outbound traffic spike detected after business hours.

### ⚠️ Indicators
- Large outbound transfer  
- Unknown external IP destination  
- Encrypted traffic anomaly  

### 🧪 Investigation Steps
1. Reviewed firewall logs  
2. Analyzed NetFlow data  
3. Correlated SIEM alerts  
4. Inspected endpoint processes  

### 🛑 Containment
Blocked outbound IP at firewall.

### 🧹 Eradication
Removed unauthorized remote access tool.

### 🔄 Recovery
Monitored traffic for recurrence.

### 📘 Lessons Learned
Network monitoring enables early detection of potential exfiltration.

---

## 📁 Case Study 07 – Improper File Permissions

**Domain Alignment:** Governance & Risk  

### 🔍 Incident
Confidential HR files accessible to non-HR employees.

### ⚠️ Indicators
- Excessive inherited permissions  
- Broad security group membership  

### 🧪 Investigation Steps
1. Reviewed NTFS permissions  
2. Audited group memberships  
3. Reviewed file access logs  
4. Identified policy violation  

### 🛑 Containment
Removed unauthorized access.

### 🧹 Eradication
Implemented least privilege access model.

### 🔄 Recovery
Performed organization-wide permission audit.

### 📘 Lessons Learned
Regular access reviews prevent privilege creep.

---

# 📊 Skills Demonstrated

- Incident response lifecycle management  
- Log and SIEM analysis  
- Threat detection and containment  
- Vulnerability validation and remediation  
- Cloud security configuration  
- Identity and access control management  
- Risk assessment and mitigation  

---

# 🛠 Tools & Technologies Referenced

- SIEM platform  
- Antivirus / EDR solution  
- Firewall logs  
- NetFlow monitoring  
- Vulnerability scanner  
- Cloud IAM console  
- Threat intelligence databases  

---

# 🎯 Certification Alignment

This portfolio aligns to the following Security+ domains:

- General Security Concepts  
- Threats, Vulnerabilities & Mitigations  
- Security Architecture  
- Security Operations  
- Security Program Management & Oversight  

---

# 📈 Professional Development Goal

These documented case studies demonstrate readiness for:

- SOC Analyst (Tier 1)  
- Junior Security Analyst  
- Cybersecurity Technician  
- IT Security Specialist  
