# 📄 Nmap Scan Report - Task 1

## 🎯 Objective
Perform a network scan using **Nmap** to identify open ports, running services, and operating system information on a target machine (`192.168.1.19`).

---

## 🧰 Tools Used
- **Tool**: Nmap 7.95  
- **Platform**: Kali Linux

---


## 🎬 Demo

[![Watch the demo](https://img.youtube.com/vi/GZys-XZ-h64/0.jpg)](https://youtu.be/GZys-XZ-h64)


---

## 🧪 Command Executed
```bash
nmap -sS -sV -O -oN nmap_results.txt 192.168.1.19
