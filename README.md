# MySQL Backup to S3 using Ansible

> 🚀 This playbook automates the process of backing up a MySQL database and uploading the dump file to an S3 bucket.

---

## ✅ Prerequisites

- [x] MySQL installed and running on the target server  
- [x] AWS CLI installed and configured with proper credentials  
- [x] Ansible installed on the control node  
- [x] S3 bucket `mysql-dump` created in AWS  

---
🔐 Security Note
⚠️ Avoid hardcoding passwords in playbooks. Instead, use variables or Ansible Vault

---
🔄 Run the Playbook: 
-
 ansible-playbook -i inventory.ini playbook.yml
