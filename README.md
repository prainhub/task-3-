# 🔐 CodTech Penetration Testing Toolkit

A modular Python-based penetration testing toolkit developed as part of the **CodTech Internship**. This toolkit helps identify common vulnerabilities in networks and websites through simple scanning techniques.

---

## 📁 Toolkit Modules

### 1. Port Scanner
Scans the target IP for open ports from a predefined list.

### 2. FTP Brute Forcer
Tries multiple passwords against an FTP server using a dictionary (wordlist) attack.

### 3. Directory Scanner
Scans a target website for hidden or commonly used directories using a wordlist.

### 4. IP Info Lookup
Fetches the location and ISP details of a public IP using `ip-api.com`.

---

## ⚙️ Requirements

- Python 3.x installed
- Install required library:

```bash
pip install requests
python main.py
1. Port Scanner
2. FTP Brute Forcer
3. Directory Scanner
4. IP Info Lookup
5. Exit
=== CodTech Penetration Testing Toolkit ===
Choose an option (1-5): 1
Enter target IP: 192.168.43.200

[OPEN] Port 8080
Choose an option (1-5): 3
Enter website URL: http://testphp.vulnweb.com
Path to wordlist.txt: wordlist.txt

[FOUND] http://testphp.vulnweb.com/admin
Choose an option (1-5): 4
Enter IP address: 8.8.8.8

IP: 8.8.8.8
Country: United States
Region: Virginia
ISP: Google LLC
