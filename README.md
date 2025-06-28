# Bash System Provisioning & Backup Scripts

This repository includes two Bash scripts developed for CYB-300 (System and Communication Security) to automate Linux system administration tasks. The scripts demonstrate group/user creation, system provisioning, and local folder backup with redundancy.

---

## 🛠️ Script 1: `adminAdd.sh` – User and Group Automation

This script:
- Creates organizational groups: `Human_Resources`, `Finance`, and `Sales`
- Creates 12 users with default credentials
- Assigns all users to the `Sales` group
- Prevents duplicate group/user creation by checking system state

### Features:
- Conditional logic using `getent` and `id`
- Echo output for audit trail
- Modular loop structure for readability

---

## 🛠️ Script 2: `backup.sh` – Redundant Folder Backup

This script:
- Creates two user directories: `user1` and `user2`
- Generates compressed backups of both folders
- Prevents overwriting existing backups using conditional logic

### Features:
- Automatic tar.gz creation
- Error handling for existing files
- Variables for reusable paths and cleaner code

---

## 📁 Directory Structure
![Screenshot 2025-06-28 112319](https://github.com/user-attachments/assets/c4e0301b-69fc-4437-be3d-22d7ba000b0c)



---

## 🧠 Project Purpose

These scripts showcase my ability to:
- Automate repetitive admin tasks with Bash  
- Write readable, error-tolerant code  
- Follow real-world provisioning logic used in security labs and cloud operations  

This work lays the foundation for larger automation efforts like hardening endpoints, configuring access control, and running compliance scripts.

---

## 🧪 Sample Output

- ✅ “Group already exists.”  
- ✅ “User ‘Users5’ created and added to group ‘Sales’.”  
- ✅ “Backup for user1 created successfully.”

(*See `/screenshots` for terminal logs and live execution.*)

---

## 👩🏽‍💻 Author

**Marjean Mayo-Baker**  
Cybersecurity Engineer | Bash Automation | IAM Specialist  
[LinkedIn](https://linkedin.com/in/marjean-mayo-baker)


