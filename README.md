# 🔐 Task 4: Setup and Use a Firewall (UFW) on Ubuntu

## 🎯 Objective
Configure and test basic firewall rules to allow or block network traffic using *UFW (Uncomplicated Firewall)* on a Linux system.

---

## 🛠 Tools Used
- Ubuntu Terminal
- UFW (Uncomplicated Firewall)

---

## ✅ Steps Performed

1. *Checked UFW status*
   - Command: sudo ufw status
   - Output: Status was inactive

2. *Updated Package List*
   - Command: sudo apt update

3. *Installed UFW*
   - Command: sudo apt install ufw

4. *Enabled the Firewall*
   - Command: sudo ufw enable
   - Output: Firewall is active and enabled on system startup

5. *Listed Current Rules*
   - Command: sudo ufw status numbered

6. *Blocked Port 23 (Telnet)*
   - Command: sudo ufw deny 23

7. *Allowed Port 22 (SSH)*
   - Command: sudo ufw allow 22

8. *Removed Telnet Block Rule*
   - Command: sudo ufw delete deny 23

9. *Verified Final Status*
   - Command: sudo ufw status

---

## 📸 Screenshots
All steps above were captured via terminal screenshots and added in the screenshots/ folder.

---

## 📌 Summary
Successfully configured UFW to:
- Block insecure traffic (Telnet on port 23)
- Allow secure traffic (SSH on port 22)
- Learn to manage firewall rules using the Linux command line.

This task helped in building a foundational understanding of *firewall configuration, **network filtering, and **security best practices* using Linux.

---

## 🧠 Key Concepts
- UFW configuration
- Network port management
- Firewall rule creation and deletion
- Linux terminal-based system security
