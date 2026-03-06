# 🌐 Network Troubleshooting Case Studies
_A collection of real-world networking scenarios aligned with CompTIA Network+ objectives._

---

## 🔌 Case Study 01 – No Network Connectivity (Layer 1 Issue)

**Category:** Physical Layer (OSI Layer 1)  
**Environment:** Office Workstation  

### 🔍 Problem
Workstation cannot access network resources.

### ⚠️ Symptoms
- No link light on NIC  
- “Network cable unplugged” message  

### 🧪 Diagnostic Process
1. Verified Ethernet cable connection  
2. Tested alternate patch cable  
3. Switched to known-good switch port  
4. Checked NIC status in Device Manager  

### ✅ Resolution
Replaced defective Ethernet cable.

### 📘 Lessons Learned
Always validate Layer 1 connectivity before escalating to higher-layer troubleshooting.

---

## 🌍 Case Study 02 – DNS Resolution Failure

**Category:** Name Resolution  

### 🔍 Problem
User can access websites via IP address but not by domain name.

### ⚠️ Symptoms
- `ping 8.8.8.8` works  
- `ping google.com` fails  

### 🧪 Diagnostic Process
1. Ran `ipconfig /all` to verify DNS server  
2. Used `nslookup` to test DNS resolution  
3. Flushed DNS cache with `ipconfig /flushdns`  
4. Verified DHCP settings  

### ✅ Resolution
Corrected incorrect DNS server configuration.

### 📘 Lessons Learned
If IP connectivity works but names fail, suspect DNS immediately.

---

## 🏢 Case Study 03 – VLAN Misconfiguration

**Category:** Switching / VLANs  

### 🔍 Problem
User unable to access internal file server.

### ⚠️ Symptoms
- Can reach internet  
- Cannot reach internal resources  

### 🧪 Diagnostic Process
1. Verified IP addressing scheme  
2. Checked switch port VLAN assignment  
3. Confirmed trunk port configuration  
4. Reviewed routing between VLANs  

### ✅ Resolution
Corrected switch port to proper VLAN assignment.

### 📘 Lessons Learned
Incorrect VLAN configuration can isolate devices even when internet connectivity works.

---

## 🔐 Case Study 04 – VPN Tunnel Not Establishing

**Category:** Remote Access / Security  

### 🔍 Problem
Remote employee cannot establish VPN tunnel.

### ⚠️ Symptoms
- Timeout during connection attempt  
- No internal resource access  

### 🧪 Diagnostic Process
1. Verified public IP reachability  
2. Confirmed firewall ports open  
3. Reviewed VPN client configuration  
4. Checked authentication logs  

### ✅ Resolution
Opened required VPN ports on firewall.

### 📘 Lessons Learned
VPN failures often involve firewall or NAT configuration issues.

---

## 🚦 Case Study 05 – Network Performance Degradation

**Category:** Performance / Monitoring  

### 🔍 Problem
Users report slow file transfers and VoIP interruptions.

### ⚠️ Symptoms
- High latency  
- Packet loss  
- Jitter during calls  

### 🧪 Diagnostic Process
1. Ran continuous `ping` tests  
2. Used `tracert` to identify latency hops  
3. Checked switch interface utilization  
4. Reviewed QoS configuration  

### ✅ Resolution
Reconfigured QoS to prioritize VoIP traffic.

### 📘 Lessons Learned
Proper QoS configuration prevents latency-sensitive application disruption.

---

## 🔁 Case Study 06 – DHCP Scope Exhaustion

**Category:** IP Addressing  

### 🔍 Problem
New devices unable to obtain IP address.

### ⚠️ Symptoms
- Devices assigned APIPA (169.254.x.x)  
- “Limited connectivity”  

### 🧪 Diagnostic Process
1. Checked DHCP server scope  
2. Reviewed lease duration  
3. Verified DHCP server availability  
4. Examined event logs  

### ✅ Resolution
Expanded DHCP scope and reduced lease duration.

### 📘 Lessons Learned
IP exhaustion can silently disrupt network onboarding.

---

## 🔥 Case Study 07 – Firewall Blocking Application Traffic

**Category:** Network Security  

### 🔍 Problem
Internal application unable to communicate with external API.

### ⚠️ Symptoms
- Application timeout errors  
- Successful internal connectivity  

### 🧪 Diagnostic Process
1. Tested port connectivity using `telnet`  
2. Reviewed firewall rule base  
3. Checked NAT policies  
4. Examined security logs  

### ✅ Resolution
Created outbound firewall rule permitting required port.

### 📘 Lessons Learned
Firewall rules must align with application communication requirements.

---

## 📡 Case Study 08 – Wireless Interference

**Category:** Wireless Networking  

### 🔍 Problem
Users experience intermittent Wi-Fi drops.

### ⚠️ Symptoms
- Signal fluctuation  
- Reduced throughput  

### 🧪 Diagnostic Process
1. Conducted wireless site survey  
2. Checked channel overlap  
3. Verified AP placement  
4. Reviewed firmware version  

### ✅ Resolution
Changed wireless channel to reduce interference.

### 📘 Lessons Learned
Channel overlap and RF interference significantly impact wireless stability.

---

# 📊 Skills Demonstrated

- OSI layer troubleshooting  
- DNS and DHCP configuration  
- VLAN management  
- Firewall rule analysis  
- VPN configuration  
- QoS optimization  
- Wireless diagnostics  
- Network performance monitoring  

---

# 🧠 Network+ Troubleshooting Methodology Applied

1. Identify problem  
2. Establish theory  
3. Test theory  
4. Establish plan of action  
5. Implement solution  
6. Verify functionality  
7. Document findings  

(Aligned with CompTIA Network+ objectives)

---

# 🛠️ Tools Utilized

- `ipconfig`
- `ping`
- `tracert`
- `nslookup`
- `netstat`
- DHCP Manager
- Switch CLI
- Firewall management console
- Wireless analyzer tools
