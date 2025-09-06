# Metasploitable 3 Pentesting Project

## 📌 Overview
This repository documents my penetration testing practice and learning process using **Metasploitable 3**, a vulnerable virtual machine created by Rapid7 for security researchers and students.  

The goal of this project is to explore and demonstrate common attack vectors, vulnerabilities, and exploitation techniques in a safe lab environment.  

⚠️ **Disclaimer**: All testing is performed on Metasploitable 3 in a controlled lab setup. This repository is strictly for **educational purposes** only. Do not attempt these techniques on systems you do not own or have explicit permission to test.  

---

## 🛠️ Lab Setup
- **Target VM**: Metasploitable 3 (Windows)  
- **Attacker VM**: Kali Linux 
- **Hypervisor**: VirtualBox  

---

## 🔍 Pentesting Methodology
1. **Information Gathering**  
   - Network discovery  
   - Service and port scanning (`nmap`)  
   - Banner grabbing  

2. **Vulnerability Analysis**  
   - Enumerating services (FTP, SMB, MySQL, RDP, HTTP, etc.)  
   - Checking for known CVEs and misconfigurations  

3. **Exploitation**  
   - Using Metasploit modules to exploit vulnerable services  
   - Manual exploitation (SQL injection, weak passwords, misconfigured services)  

4. **Post-Exploitation**  
   - Privilege escalation  
   - Loot collection (hashes, sensitive files, database dumps)  
   - Persistence  

---

## 📂 Repository Contents
- `notes/` → Pentesting notes, commands, and outputs  
- `screenshots/` → Screenshots of findings and exploitation steps  
- `reports/` → Structured penetration testing reports  

---

## 🚀 Tools Used
- [Metasploit Framework](https://www.metasploit.com/)  
- [Nmap](https://nmap.org/)  
- [Hydra](https://github.com/vanhauser-thc/thc-hydra)  

---

## 📖 Learning Objectives
- Practice a full **penetration testing lifecycle**  
- Understand real-world vulnerabilities and exploits  
- Improve skills with Metasploit and manual exploitation techniques  
- Document findings in a professional format  

---

## ✅ Status
- [x] Lab setup complete  
- [x] Initial scanning and enumeration  
- [ ] Exploitation phase (in progress)  
- [ ] Report writing  

---


