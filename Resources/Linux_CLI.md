# Linux Command Line Toolkit

This document outlines essential Linux command-line tools and their use in
system administration and troubleshooting scenarios.

Distribution Used: Ubuntu 22.04
Environment: VirtualBox Lab
Shell: Bash

---

# 1. File & Directory Management

## pwd
Purpose: Displays current directory.

## ls
Common Usage:
- ls
- ls -la
- ls -lh

Used For:
- Viewing hidden files
- Checking permissions
- Reviewing file sizes

---

## cd
Purpose: Navigate directories.

---

## cp
Purpose: Copy files/directories.

Common Usage:
- cp file.txt backup.txt
- cp -r folder/ backup/

---

## mv
Purpose: Move or rename files.

---

## rm
Common Usage:
- rm file.txt
- rm -r folder/

Used For:
- Removing files or directories

---

# 2. File Viewing & Text Processing

## cat
Purpose: Display file contents.

## less
Purpose: View large files page-by-page.

## head / tail
Common Usage:
- head -n 10 file.txt
- tail -f logfile.log

Used For:
- Monitoring logs in real time

---

## grep
Purpose: Search for patterns in files.

Example:
- grep "error" logfile.log

Used For:
- Log analysis
- Security investigations

---

# 3. Permissions & Ownership

## chmod
Purpose: Modify file permissions.

Example:
- chmod 755 script.sh

---

## chown
Purpose: Change file ownership.

Example:
- chown user:group file.txt

---

## ls -l
Used For:
- Reviewing permission structure

---

# 4. System Monitoring

## top
Purpose: View real-time resource usage.

## ps
Common Usage:
- ps aux

Used For:
- Identifying running processes

---

## kill
Purpose: Terminate processes.

Example:
- kill -9 PID

---

## df
Purpose: Display disk usage.

## du
Purpose: Show directory space usage.

---

# 5. Networking Commands

## ip
Common Usage:
- ip a
- ip route

Used For:
- Checking IP address
- Reviewing routing table

---

## ping
Purpose: Test connectivity.

---

## netstat (legacy) / ss
Purpose: View open ports and connections.

Example:
- ss -tuln

Used For:
- Identifying listening services
- Security troubleshooting

---

## traceroute
Purpose: Trace network path.

---

# 6. Package Management (Ubuntu/Debian)

## apt update
## apt upgrade
## apt install
## apt remove

Used For:
- Software installation
- System patching

---

# 7. User Management

## whoami
Purpose: Identify current user.

## sudo
Purpose: Execute command as superuser.

## adduser
Purpose: Create new user.

## passwd
Purpose: Change user password.

---

# 8. Log File Analysis

Log Location:
- /var/log/

Common Logs:
- syslog
- auth.log

Example:
- tail -f /var/log/auth.log
- grep "Failed password" /var/log/auth.log

Used For:
- Investigating login failures
- Monitoring authentication attempts

---

# Troubleshooting Example

Scenario: Web server not responding.

Steps:
1. ping server_ip
2. ss -tuln (Check if port 80/443 is listening)
3. systemctl status apache2
4. tail -f /var/log/syslog
5. Restart service if necessary

---

# Applied Lab Projects

- Created 3 Linux VMs in VirtualBox
- Configured static IP address
- Created users and groups
- Set file permissions and tested access control
- Installed and configured Apache web server

---

# Reflection

Through hands-on labs, I have demonstrated independent ability to:
- Navigate Linux systems
- Manage users and permissions
- Troubleshoot services
- Analyze system logs
