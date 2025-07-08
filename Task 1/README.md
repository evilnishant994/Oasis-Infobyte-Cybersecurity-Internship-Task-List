# 📄 Nmap Scan Report - Task 1

## 🎯 Objective
Perform a network scan using **Nmap** to identify open ports, running services, and operating system information on a target machine (`192.168.1.19`).

---

## 🧰 Tools Used
- **Tool**: Nmap 7.95  
- **Platform**: Kali Linux

---


## 🎬 Demo Video

[![Watch the demo](https://youtu.be/rcF4lMJzHQ4)

🔗 [Click here to watch the video on YouTube](https://youtu.be/rcF4lMJzHQ4)

---

## 🧪 Command Executed
```bash
nmap -sS -sV -O -oN nmap_results.txt 192.168.1.19
