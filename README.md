
 
 
 _   _ __  __                       _             
| \ | |  \/  |   __ _ _ __ ___   __| | ___  _ __  
|  \| | |\/| |  / _` | '__/ _ \ / _` |/ _ \| '_ \ 
| |\  | |  | | | (_| | | | (_) | (_| | (_) | | | |
|_| \_|_|  |_|  \__,_|_|  \___/ \__,_|\___/|_| |_|

         Nmap Basics — Lab 
         

---

## 📌 Objectives

- Understand and execute core Nmap scan types
- Interpret scan outputs for ports, services, and OS info
- Practice safe, permission-based reconnaissance
- Build a reusable cheatsheet and scan archive

---
## 🔍 Scan Modules

Each scan includes:
- ✅ Command used
- 📄 Output summary
- 🧠 Key takeaways
- 🖼 Screenshot placeholder

Performs a full TCP handshake. Useful When SYN scan isn't possible.

📄 Output: Lists open TCP ports
🧠 Takeaway: Easy to run without root, but more detectable


Service & Version Detection (-sV)

Identifies services and their versions on open ports.
📄 Output: Reveals software names and versions
🧠 Takeaway: Enables targeted CVE lookups


Aggressive Scan (-A)

sudo nmap -A < target ip >
Identifies services and their versions on open ports.
📄 Output: Reveals software names and versions
🧠 Takeaway: Enables targeted CVE lookups



Tutorial Summary

Scan examples and flags
Ethical hacking reminders
Syntax breakdown and real-world tips



🧵 Reflections

What I learned about scan types and stealth
How I'll use this in future labs



🧰 Cheatsheet

nmap -sT <target>       # TCP Connect
sudo nmap -sS <target>  # SYN Scan
nmap -sV <target>       # Service Detection
sudo nmap -O <target>   # OS Detection
sudo nmap -A <target>   # Aggressive Scan


!!!!!!!!!!!!!!!!! 🚨 Ethics Reminder !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
This lab is for educational purposes only. Always scan with permission.
