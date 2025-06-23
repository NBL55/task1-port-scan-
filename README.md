# task1-port-scan-
Nmap port scanning and Wireshark analysis to identify open ports and assess network exposure 
> 🔐 Internship Task 1: Performed a TCP SYN scan on the local network using Nmap, captured packets with Wireshark, and analyzed protocol behavior and potential risks.
# 🛡️ Task 1 - Network Port Scanning & Wireshark Analysis

## 🎯 Objective
Perform a TCP SYN scan using Nmap to discover open ports on devices in the local network and analyze packet-level traffic using Wireshark.

---

## 🔧 Tools Used
- **Nmap** — for scanning open TCP ports
- **Wireshark** — for packet capture and protocol-level analysis
- **OS** — Windows 11 (or Kali Linux, if applicable)

---

## 📍 Nmap Command Used

```bash
nmap -sS 192.168.56.0/24 -oN scan_results.txt
