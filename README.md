# Cybersecurity Internship - Task 1: Network Port Scanning

## 🔍 Objective
To scan the local network and discover open ports using Nmap.

## 🛠 Tools Used
- Nmap 7.97

## 🌐 Network Information
- Local IP: 192.168.8.72
- Scanned Range: 192.168.8.0/24
- Hosts Found: 2

## 📊 Scan Summary

### 📌 Host 1: 192.168.8.243
- Open Port: 53 (DNS)
- Possible Device: Router or DNS Server

### 📌 Host 2: 192.168.8.71
- Open Ports:
  - 135 (msrpc)
  - 139 (netbios-ssn)
  - 445 (microsoft-ds)
- Possible Device: Windows Machine

## ⚠️ Risk Analysis
- Port 445 and 139 are commonly targeted in Windows SMB exploits.
- DNS port should be monitored for unusual activity.

## ✅ Recommendations
- Disable unused ports and services.
- Use firewall rules to restrict access to internal systems.
- Regularly monitor network activity for anomalies.

## 📁 Files in Repo
- `task1.txt`: Nmap scan results
- `README.md`: Task summary and analysis

---
