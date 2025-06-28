# Bash System Provisioning Script

This repository contains a Bash-based automation script designed to provision and harden newly deployed Linux systems in enterprise or lab environments.

The script handles core system setup tasks including hostname configuration, timezone alignment, service lockdown, log exports, and final provisioning cleanup.

---

## 🛠️ Key Functions

- 🖥️ Set system hostname via `hostnamectl`
- 🌐 Configure system timezone (e.g., America/Denver)
- 🔐 Enforce idle lockout via `gsettings`
- 🧩 Log active processes to `process.txt`
- 📂 Extract recent entries from `/var/log/syslog` to `security_log.txt`
- ⚙️ Bundle steps into one executable script (`finalScript.sh`)

---

## 🧠 Purpose

This script was developed as part of a broader system hardening and asset relocation strategy. It allows fast deployment of secure configurations without requiring GUI access or manual entry, making it ideal for cloud provisioning, security lab builds, or red team infrastructure setup.

---

## 📁 File Structure

![Screenshot 2025-06-28 112319](https://github.com/user-attachments/assets/0bf04dab-3ded-41e5-847c-e0af167ffb71)

---

## 📸 Screenshots

- Terminal execution of `finalScript.sh`
- Output of `process.txt`
- Log export confirmation

---

## 🚧 Status

✅ Script completed and tested  
🧠 Additional modular options being explored (e.g., firewall, cron auditing)

---

## 🔐 Use Cases

- SOC lab builds  
- Remote endpoint provisioning  
- SecOps deployment templates  
- Cybersecurity portfolio evidence

---

## 👩🏽‍💻 Author

**Marjean Mayo-Baker**  
Cybersecurity Engineer | Bash Automation | Incident Response  
[LinkedIn](https://linkedin.com/in/marjean-mayo-baker)
