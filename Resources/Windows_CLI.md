# Windows Command Line Toolkit

This document outlines essential Windows Command Line Interface (CLI) tools 
and their practical use in IT support and troubleshooting scenarios.

Environment: Windows 10 / Windows 11  
Shells Used: Command Prompt (CMD), PowerShell

---

# 1. Network Diagnostics Commands

## ipconfig
Purpose: Displays IP configuration information.

Common Usage:
- ipconfig
- ipconfig /all
- ipconfig /release
- ipconfig /renew
- ipconfig /flushdns

Used For:
- Verifying DHCP assignment
- Identifying IP conflicts
- Troubleshooting DNS issues

---

## ping
Purpose: Tests network connectivity.

Common Usage:
- ping 8.8.8.8
- ping google.com

Used For:
- Testing gateway connectivity
- Verifying external internet access
- Identifying DNS resolution problems

---

## tracert
Purpose: Traces path packets take to destination.

Used For:
- Identifying network latency
- Isolating routing problems

---

## nslookup
Purpose: Queries DNS servers.

Used For:
- Verifying DNS resolution
- Checking name server records

---

# 2. System Diagnostics Commands

## sfc
Purpose: Scans and repairs system files.

Common Usage:
- sfc /scannow

Used For:
- Fixing corrupted Windows files
- Troubleshooting system crashes

---

## chkdsk
Purpose: Checks disk integrity.

Common Usage:
- chkdsk C:
- chkdsk C: /f /r

Used For:
- Identifying bad sectors
- Fixing file system errors

---

## tasklist
Purpose: Displays running processes.

Used For:
- Identifying high resource usage
- Finding suspicious processes

---

## taskkill
Purpose: Terminates processes.

Common Usage:
- taskkill /PID 1234 /F

Used For:
- Stopping frozen applications

---

# 3. User & Account Management

## net user
Purpose: Manages user accounts.

Common Usage:
- net user
- net user username *
- net user username /active:no

Used For:
- Resetting passwords
- Disabling accounts

---

## whoami
Purpose: Displays current logged-in user.

Used For:
- Verifying user permissions
- Confirming account context

---

# 4. Network & Port Analysis

## netstat
Purpose: Displays active network connections.

Common Usage:
- netstat -an
- netstat -b

Used For:
- Identifying open ports
- Detecting suspicious connections

---

## arp
Purpose: Displays ARP table.

Used For:
- Identifying MAC-to-IP mappings
- Troubleshooting local network conflicts

---

# 5. System Information & Maintenance

## systeminfo
Purpose: Displays detailed system configuration.

Used For:
- Checking OS version
- Verifying RAM and CPU details

---

## gpupdate
Purpose: Updates Group Policy settings.

Common Usage:
- gpupdate /force

Used For:
- Applying new domain policies

---

# 6. Disk & File Management

## diskpart
Purpose: Disk management utility.

Used For:
- Creating partitions
- Assigning drive letters

---

## robocopy
Purpose: Robust file copy tool.

Used For:
- Backups
- Large file transfers

---

# Troubleshooting Methodology Example

Scenario: User cannot access internet.

Steps:
1. ipconfig /all (Verify IP address)
2. ping gateway (Test local connectivity)
3. ping 8.8.8.8 (Test external connectivity)
4. nslookup google.com (Verify DNS)
5. ipconfig /flushdns (Clear DNS cache)

---

# Skill Development Reflection

Through hands-on labs and troubleshooting simulations, I have demonstrated 
independent execution of these commands in real-world scenarios.
