from pathlib import Path

# Create an extended description for each file
admin_desc = """\
## 📁 adminAdd_cleaned.sh

This script is designed to automate the provisioning of Linux user groups and batch user creation with access control.

### Functionality:
- Creates three key organizational groups: Human_Resources, Finance, and Sales.
- Checks for the existence of each group using `getent group`.
- Creates twelve user accounts (Users1 through Users12) if they do not already exist.
- Sets default passwords for new users and adds them to the 'Sales' group.
- Includes error handling and output for auditing actions.

### Skills Demonstrated:
- Bash scripting fundamentals
- Conditional logic with `if`, `else`
- Looping with `for`
- Secure user provisioning and group management
"""

backup_desc = """\
## 💾 backup_cleaned.sh

This script provides a redundant backup system for two user directories on a Linux system.

### Functionality:
- Automatically creates user1 and user2 directories on the desktop.
- Generates `.tar.gz` compressed backups of each directory.
- Checks if a backup already exists to avoid overwriting.
- Prints confirmation messages for successful backup or skip logic.

### Skills Demonstrated:
- Backup and archiving with `tar`
- File existence checks with `-f`
- Loop iteration for repeatable actions
- Redundancy and recovery planning in Bash
"""

terminal_desc = """\
## 🖥️ terminal_history (Extracted Commands)

This file captures a real session of Bash script testing and system interaction.

### Highlights:
- Command-by-command development of the `adminAdd.sh` and `backup.sh` scripts
- Use of `sudo`, `groupadd`, `useradd`, `chpasswd`, and `tar` commands
- Demonstrates iterative testing, troubleshooting, and Linux admin task verification
- Shows awareness of system permissions and secure user management practices

### Use Case:
Ideal for instructors, reviewers, or hiring managers to verify hands-on command-line usage.
"""

# Combine all descriptions into a single README
readme_content = f"""\
# 🔐 Linux Admin Automation Projects

This repository contains two Bash scripts created for CYB-300 (System and Communication Security) focused on automating core administrative tasks in Linux environments.

---

{admin_desc}

---

{backup_desc}

---

{terminal_desc}

---

## Author

**Marjean Mayo-Baker**  
