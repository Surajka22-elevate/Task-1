Screenshots:-
![image](https://github.com/user-attachments/assets/1c8795fb-4d4c-4e91-b1d4-90efa2f8faa1)
![image](https://github.com/user-attachments/assets/682998e2-4acc-4254-b809-a2a06d04323e)



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
