# 🔍 Local Network Port Scan using Nmap

This project demonstrates how to perform a TCP SYN scan on a local network using Nmap to identify open ports and potential security risks.

## 🛠 Tools Used
- *Nmap* – for scanning open TCP ports
- *Kali Linux (VirtualBox)* – as the host system

## 📡 Scan Information
- *Target Network:* 10.0.2.0/24
- *Scan Type:* TCP SYN scan (-sS)
- *Command Used:*
  ```bash
  nmap -sS 10.0.2.0/24 -oN scan_results.txt
