# 🔐 Packet Tracer Lab: Configure Basic Wireless Security

> Hands-on wireless security configuration using WPA2-Personal - SOC Analyst skill development

## 📋 Lab Overview
This practical lab demonstrates how to configure and verify WPA2-Personal wireless security using Cisco Packet Tracer. As an aspiring SOC Analyst, understanding network security fundamentals is crucial for monitoring, detecting threats, and protecting enterprise environments.

## 🎯 Objectives Accomplished
- ✅ Configured WPA2-Personal security on a wireless router
- ✅ Updated client devices with new security credentials  
- ✅ Verified connectivity before and after security implementation
- ✅ Documented the entire process for reproducibility

## 🛠️ Technical Steps Performed

### Part 1: Baseline Connectivity Verification
- Accessed web browser on client laptop
- Verified initial connectivity to `www.cisco.pka`
- Established baseline for security comparison

### Part 2: Wireless Security Configuration
1. Accessed wireless router at `192.168.1.1`
2. Configured 2.4GHz network with WPA2-Personal security
3. Set strong passphrase for network encryption
4. Saved and applied security settings

### Part 3: Client Device Configuration
1. Updated laptop wireless settings
2. Connected to secured SSID with new credentials
3. Established encrypted wireless connection

### Part 4: Post-Security Verification
- Re-tested connectivity to verify successful implementation
- Confirmed security configuration didn't break functionality
- Documented the entire hardening process

## 🖼️ Lab Screenshots

### 1. WPA2 Configuration on Wireless Router
![WPA2 Configuration](screenshots/01-wpa2-configuration.png)
*Configuring WPA2-Personal with AES encryption on the wireless router*

### 2. Laptop Connecting to Secured Network
![Laptop Connection](screenshots/02-laptop-connection.png)  
*Laptop successfully connecting to the secured "Academy" SSID*

### 3. Verification of Successful Connection
![Verification](screenshots/03-verification.png)
*Final verification showing successful web access after security implementation*

## 🛡️ SOC Analyst Relevance

| Lab Component | SOC Application |
|--------------|----------------|
| **Security Hardening** | Understanding how security controls are implemented and validated |
| **Configuration Management** | Tracking and verifying security configuration changes |
| **Verification Testing** | Ensuring security implementations don't break functionality |
| **Documentation** | Creating clear records for audits and investigations |
| **Wireless Security** | Monitoring for rogue APs and unauthorized wireless access |

## 📚 Key Cybersecurity Takeaways
1. **Security requires proactive configuration** - Default settings are often insecure
2. **Always verify after implementation** - Changes must be tested and validated
3. **Documentation is critical** - Clear records aid troubleshooting and compliance
4. **Wireless networks are high-risk** - Proper encryption is essential for confidentiality
5. **End-to-end validation** - Both server and client configurations must align

## 🔧 Files in This Repository
- `Configure Basic Wireless Security.htm` - Original lab instructions and procedures
- `screenshots/` - Visual documentation of lab execution
  - `01-wpa2-configuration.png` - Router security configuration
  - `02-laptop-connection.png` - Client connection process
  - `03-verification.png` - Post-implementation verification

## 🚀 Next Learning Steps
- Analyze wireless traffic with Wireshark to understand encryption in action
- Research and compare WPA2 vs WPA3 security protocols
- Explore wireless attack techniques (KRACK, evil twin, etc.) and their detection
- Practice creating detection rules for wireless security events

## 👨‍💻 About the Author
I'm an aspiring SOC Analyst building practical cybersecurity skills through hands-on labs and projects. This repository documents my journey in developing the technical foundations needed for security operations.



---
*Lab completed as part of cybersecurity skill development for SOC Analyst career path.*# wireless-security-lab
Packet Tracer lab for WPA2 configuration - SOC Analyst learning
