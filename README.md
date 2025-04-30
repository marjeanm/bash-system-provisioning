# 🛠️ Linux System Automation Scripts – CYB-300

A collection of Bash automation scripts designed to streamline user provisioning and backup management on Linux systems. Created as part of the CYB-300 System and Communication Security course.

---

## 📁 `adminAdd.sh`: User and Group Provisioning Script

This script automates the creation of user groups and bulk user accounts while enforcing basic security standards like password initialization and group-based access control.

### Features:
- Creates standard departments: `Human_Resources`, `Finance`, `Sales`
- Adds 12 unique users (Users1 to Users12)
- Sets a default secure password for each user
- Assigns each user to the `Sales` group
- Prevents duplicate users or groups from being created
- Includes detailed inline documentation for readability

---

## 💾 `backup.sh`: Redundant Backup Script

Automates backup creation for critical folders with built-in error checking and redundancy.

### Features:
- Creates two user folders (`user1`, `user2`) on the Desktop
- Archives each folder as a `.tar.gz` backup with timestamps
- Checks for existing backup files before overwriting
- Uses `tar` for efficient compression
- Includes basic verification step via `ls -l`

---

## 🚀 Skills Demonstrated
- Bash scripting and iteration logic
- Error checking and conditional logic
- Linux system administration
- Secure user provisioning
- File compression and backup automation

---

## 📌 Author

**Marjean Mayo-Baker**  
CYB-300 | Southern New Hampshire University  
[GitHub](https://github.com/marjeanm) • [LinkedIn](https://www.linkedin.com/in/marjean-mayo-baker/) • [TheDigitalRuins.com](https://thedigtialruins.com)
