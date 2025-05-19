# 🛡️ AWS Backup

---

## 📌 Description  
**AWS Backup** is a **fully managed backup service** that enables you to **centralize and automate data backup** across AWS services (and some on-premises apps). It ensures compliance, security, and recovery readiness with minimal manual effort.

---

## 🚀 Key Features  
- 📅 **Scheduled Backups**: Automate backup tasks using backup plans  
- 🧩 **Cross-service support**: Works with EC2, EBS, RDS, DynamoDB, FSx, EFS, Storage Gateway, and more  
- 🌍 **Cross-region & cross-account backup** for enhanced resiliency  
- 🔄 **Restore capabilities**: Quickly recover full resources or specific data  
- 📋 **Compliance tracking**: Central audit and backup activity logs  
- 🔐 **Encryption & security**: Encrypt backups using AWS KMS  
- 📊 **Backup vaults**: Logical containers to isolate and manage backup resources  

---

## 🛠️ Use Cases  
- 🛠️ **Disaster recovery planning**  
- 🗃️ **Retention policy enforcement** across environments  
- 🛡️ **Centralized governance** for backups across accounts  
- 🏢 **Regulatory compliance** for industries like finance and healthcare  
- 🔄 **Automated backup/restore** for EC2, RDS, DynamoDB, EFS, etc.  

---

## 🔁 Comparison with Similar Services  

| Service             | Difference from AWS Backup |
|---------------------|-----------------------------|
| **EBS Snapshots**   | EBS-only backup; AWS Backup supports multiple services with central control |
| **AWS DLM**         | Focused on EBS snapshots and AMIs; AWS Backup offers more resource types |
| **Third-party tools** | AWS Backup is fully integrated with AWS IAM, KMS, and policies — no extra setup required |

---

## 💰 Pricing  
- 💾 Charged per GB-month of backup storage used  
- 🔄 Restore jobs charged per GB restored  
- 🚀 Cross-region and cross-account backups may incur additional data transfer charges  
- 🧮 Pricing varies by resource type (e.g., EBS, RDS, DynamoDB)

---

## 🧠 Exam Keywords  
- "Centralized backup management"  
- "Cross-account and cross-region backups"  
- "Supports multiple AWS services (EBS, RDS, DynamoDB...)"  
- "Backup plans and vaults"  
- "Encrypt backups with KMS"
