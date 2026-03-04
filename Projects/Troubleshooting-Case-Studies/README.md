# 🛠️ Troubleshooting Case Studies
_A collection of real-world IT support scenarios demonstrating structured troubleshooting methodology._

> These troubleshooting case studies reflect hands-on lab simulations and real-world IT support scenarios aligned with CompTIA A+ objectives.
---

## 📶 Case Study 01 – Wi-Fi Connectivity Failure

**Category:** Networking  
**Environment:** Windows 11 Workstation  

### 🔍 Problem
User unable to connect to Wi-Fi.

### ⚠️ Symptoms
- Limited connectivity  
- No internet access  

### 🧪 Diagnostic Process
1. Checked IP configuration using `ipconfig /all`
2. Tested gateway connectivity with `ping`
3. Reset wireless network adapter

### ✅ Resolution
Reconfigured DNS settings to obtain automatically via DHCP.

### 📘 Lessons Learned
Always verify DHCP assignment and DNS configuration before escalating.

---

## 🔌 Case Study 02 – Random System Reboots

**Category:** Hardware / Power  
**Environment:** Desktop Workstation  

### 🔍 Problem
Computer randomly restarts without warning.

### ⚠️ Symptoms
- Sudden reboot  
- No error message  

### 🧪 Diagnostic Process
1. Reviewed Event Viewer logs  
2. Monitored CPU temperature  
3. Ran Windows Memory Diagnostics  
4. Inspected PSU connections  

### ✅ Resolution
Replaced failing Power Supply Unit (PSU).

### 📘 Lessons Learned
Unexpected reboots often indicate power delivery or hardware instability issues.

---

## 🖨️ Case Study 03 – Network Printer Failure

**Category:** Peripherals / Networking  

### 🔍 Problem
User unable to print to network printer.

### ⚠️ Symptoms
- Print jobs stuck in queue  
- Printer status shows “Ready”  

### 🧪 Diagnostic Process
1. Restarted Print Spooler service  
2. Cleared print queue  
3. Verified printer IP address  
4. Reinstalled printer driver  

### ✅ Resolution
Updated and reinstalled corrupted printer driver.

### 📘 Lessons Learned
Driver corruption is a common cause of persistent printer issues.

---

## 🚀 Case Study 04 – Slow Boot Performance

**Category:** Performance / Security  

### 🔍 Problem
System takes over 8 minutes to load desktop.

### ⚠️ Symptoms
- Extended boot time  
- Delayed application loading  

### 🧪 Diagnostic Process
1. Reviewed startup programs in Task Manager  
2. Checked disk health  
3. Verified available disk space  
4. Performed malware scan  

### ✅ Resolution
Disabled unnecessary startup applications and removed malware.

### 📘 Lessons Learned
Startup management and malware detection significantly impact system performance.

---

## 🔐 Case Study 05 – Account Lockout

**Category:** Identity & Access Management  

### 🔍 Problem
User account locked after failed login attempts.

### ⚠️ Symptoms
- “Account locked” message  

### 🧪 Diagnostic Process
1. Reviewed Local Users and Groups  
2. Checked lockout policy  
3. Analyzed Security logs in Event Viewer  

### ✅ Resolution
Reset password and unlocked account.

### 📘 Lessons Learned
Understanding account lockout thresholds prevents recurring incidents.

---

---

## 🖥️ Case Study 06 – External Monitor Not Displaying

**Category:** Hardware / Display  
**Environment:** Windows Laptop with HDMI Output  

### 🔍 Problem
External monitor not displaying.

### ⚠️ Symptoms
- Laptop screen functions normally  
- External monitor displays “No Signal”  

### 🧪 Diagnostic Process
1. Checked HDMI cable connection  
2. Tested alternate HDMI cable  
3. Verified display settings (Extend/Duplicate)  
4. Updated graphics drivers  

### ✅ Resolution
Replaced faulty HDMI cable.

### 📘 Lessons Learned
Always verify physical connections before beginning software troubleshooting.

---

## 💻 Case Study 07 – Blue Screen of Death (BSOD)

**Category:** Operating System / Drivers  

### 🔍 Problem
System displays Blue Screen error.

### ⚠️ Symptoms
- BSOD with driver-related error code  

### 🧪 Diagnostic Process
1. Booted into Safe Mode  
2. Reviewed minidump files  
3. Updated device drivers  
4. Ran `sfc /scannow`  

### ✅ Resolution
Updated outdated network adapter driver.

### 📘 Lessons Learned
Outdated or incompatible drivers are a common cause of system instability.

---

## 🌐 Case Study 08 – Browser Redirect Malware

**Category:** Security / Malware  

### 🔍 Problem
Web browser redirects to unknown websites.

### ⚠️ Symptoms
- Unexpected pop-ups  
- Homepage changes without user action  

### 🧪 Diagnostic Process
1. Reviewed installed browser extensions  
2. Ran anti-malware scan  
3. Checked proxy settings  
4. Cleared browser cache  

### ✅ Resolution
Removed malicious browser extension and reset browser settings.

### 📘 Lessons Learned
Browser extensions can introduce security vulnerabilities and persistent redirects.

---

## 🔎 Case Study 09 – USB Drive Not Recognized

**Category:** Storage / Peripheral Devices  

### 🔍 Problem
USB drive not recognized by system.

### ⚠️ Symptoms
- Device does not appear in File Explorer  

### 🧪 Diagnostic Process
1. Checked Device Manager for detection  
2. Opened Disk Management  
3. Tested alternate USB ports  
4. Updated USB controller drivers  

### ✅ Resolution
Assigned a drive letter in Disk Management.

### 📘 Lessons Learned
Removable storage devices may require manual drive letter assignment before becoming accessible.

---

## 🔐 Case Study 10 – VPN Connection Failure

**Category:** Networking / Remote Access  

### 🔍 Problem
VPN connection fails to authenticate.

### ⚠️ Symptoms
- “Authentication failed” error message  

### 🧪 Diagnostic Process
1. Verified internet connectivity  
2. Confirmed username and password  
3. Reviewed VPN server address configuration  
4. Checked system date and time synchronization  

### ✅ Resolution
Corrected incorrect VPN server configuration.

### 📘 Lessons Learned
Configuration errors often mimic credential failures; verify connection settings before resetting passwords.

---

## 🔄 Case Study 11 – Windows Updates Failing

**Category:** Operating System Maintenance  

### 🔍 Problem
Windows updates fail to install.

### ⚠️ Symptoms
- Update stuck at 0%  
- Displays system error code  

### 🧪 Diagnostic Process
1. Restarted Windows Update service  
2. Verified sufficient disk space  
3. Ran Windows Update Troubleshooter  
4. Cleared Windows Update cache  

### ✅ Resolution
Reset Windows Update components.

### 📘 Lessons Learned
System services and background components must function properly for successful patch management.

---

## 🔊 Case Study 12 – No Audio Output

**Category:** Hardware / Drivers  

### 🔍 Problem
No sound from speakers.

### ⚠️ Symptoms
- Audio icon visible  
- No playback sound  

### 🧪 Diagnostic Process
1. Checked volume mixer settings  
2. Verified correct default playback device  
3. Reinstalled audio drivers  
4. Tested with external headphones  

### ✅ Resolution
Selected correct default playback device.

### 📘 Lessons Learned
Always verify output device configuration before reinstalling drivers.

---

## 🔋 Case Study 13 – Rapid Battery Drain

**Category:** Hardware / Power Management  

### 🔍 Problem
Laptop battery drains quickly.

### ⚠️ Symptoms
- Battery lasts less than one hour  

### 🧪 Diagnostic Process
1. Generated battery report using `powercfg /batteryreport`  
2. Reviewed power settings  
3. Analyzed background applications  
4. Updated BIOS  

### ✅ Resolution
Replaced degraded battery.

### 📘 Lessons Learned
Battery health reports provide valuable lifecycle and degradation insights.

--- 

# 📊 Skills Demonstrated

- Structured troubleshooting methodology  
- Log analysis (Event Viewer)  
- Network diagnostics  
- Hardware diagnostics  
- Driver management  
- Malware remediation  
- Windows system tools usage  
- Root cause analysis  

---

# 🧠 Troubleshooting Methodology Used

Each case study follows:

1. Identify the problem  
2. Establish theory  
3. Test theory  
4. Establish plan of action  
5. Verify functionality  
6. Document findings  

(Aligned with CompTIA A+ troubleshooting framework)

---

# 🔎 Tools Utilized

- `ipconfig`
- `ping`
- Event Viewer
- Device Manager
- Disk Management
- Windows Memory Diagnostic
- Task Manager
- SFC Scan
- Windows Update Troubleshooter

