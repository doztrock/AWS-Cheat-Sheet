# 🔗 AWS Storage Gateway

---

## 📌 Description  
**AWS Storage Gateway** is a **hybrid cloud storage service** that connects your **on-premises environments** to AWS storage services. It enables you to **extend on-prem storage** to the cloud for backup, archiving, and disaster recovery while keeping local performance for frequently accessed data.

---

## 🚀 Key Features  
- 🧱 **Three gateway types**:  
  - **S3 File Gateway**: NFS/SMB interface to store files in S3  
  - **Volume Gateway**: iSCSI block storage backed by S3 with EBS snapshots  
  - **Tape Gateway**: Virtual tape library (VTL) for backup apps (replaces physical tapes)  
- 🗂️ **Local caching**: Frequently accessed data is cached locally for low latency  
- 🔄 **Automatic syncing**: Syncs to S3, EBS, or Glacier in the background  
- 🔐 **Encryption & security**: Supports encryption in transit and at rest  
- 📊 **Monitoring**: Integrates with CloudWatch for visibility and alerts  
- 🧩 **Compatible with backup tools** (e.g., Veeam, Commvault, Veritas)

---

## 🛠️ Use Cases  
- 💽 **Backup and archiving** using existing apps  
- 🏢 **Extend file storage** to AWS with minimal change  
- 🧰 **Disaster recovery** using snapshots or VTL  
- 📚 **Migrate on-prem data** to cloud gradually  
- 🎞️ **Replace tape libraries** with virtual tapes in Glacier  

---

## 🔁 Comparison with Similar Services  

| Service              | Difference from AWS Storage Gateway |
|----------------------|--------------------------------------|
| **AWS Snowball**     | For physical data transfer; Storage Gateway offers ongoing hybrid cloud integration |
| **Amazon S3**        | Storage Gateway is a bridge to S3; S3 alone doesn’t offer on-prem connectivity |
| **AWS DataSync**     | DataSync is for one-time or scheduled transfer; Storage Gateway enables continuous hybrid access |

---

## 💰 Pricing  
- 💵 **Gateway usage fee**: ~$0.01–0.03/GB-month (depending on gateway type)  
- 📦 **Storage costs**: Pay for S3, EBS snapshots, or Glacier usage  
- 🧠 **Data transfer** to AWS is free; outbound transfer has standard AWS fees  

---

## 🧠 Exam Keywords  
- "Hybrid cloud storage"  
- "File, Volume, and Tape Gateway"  
- "Connect on-prem to S3, EBS, or Glacier"  
- "NFS/SMB or iSCSI interfaces"  
- "Local cache + cloud durability"
