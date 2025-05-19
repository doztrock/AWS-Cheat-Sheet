# 💽 Amazon Elastic Block Store (Amazon EBS)

---

## 📌 Description  
**Amazon EBS** is a **block storage service** designed for use with Amazon EC2. It provides **durable, high-performance storage volumes** that can be attached to EC2 instances, ideal for applications that require persistent data like databases or file systems.

---

## 🚀 Key Features  
- 📦 **Persistent block storage**: Data is retained independently of EC2 instance lifecycle  
- 🧲 **Volume types**: Supports SSD (gp2, gp3, io1, io2) and HDD (st1, sc1) for performance or throughput  
- 🔄 **Snapshots**: Point-in-time backups to Amazon S3, used for restore or replication  
- 🚀 **High performance**: Up to 64,000 IOPS or 1,000 MB/s throughput (depending on type)  
- 🔐 **Encryption**: Integrated with AWS KMS for data-at-rest and in-transit encryption  
- ♻️ **Resizable**: Volumes can be resized and changed without downtime  
- 🔁 **Multi-Attach**: io1/io2 volumes can be attached to multiple instances in the same AZ (Linux only)

---

## 🛠️ Use Cases  
- 🛢️ **Databases** (e.g., MySQL, MongoDB) requiring fast and consistent IOPS  
- 🖥️ **Boot volumes** for EC2 instances  
- 🗂️ **File systems** and application storage  
- 🔄 **Backup and disaster recovery** with snapshots  
- 💼 **Enterprise apps** that need block-level storage

---

## 🔁 Comparison with Similar Services  

| Service       | Difference from Amazon EBS |
|----------------|----------------------------|
| **Amazon EFS** | EFS is shared file storage (NFS); EBS is block storage attached to a single EC2 instance (per AZ) |
| **Amazon S3**  | S3 is object storage; EBS is block storage for low-latency apps |
| **Instance Store** | Temporary storage tied to instance lifecycle; EBS is persistent |

---

## 💰 Pricing  
- 💵 Pay per GB-month of provisioned storage  
- 📈 Charges vary by volume type (gp3 is the default general-purpose SSD)  
- 💾 Snapshots stored in S3 incur additional charges  
- 🚚 Data transfer between AZs or to other services may incur fees  

---

## 🧠 Exam Keywords  
- "Persistent block-level storage for EC2"  
- "Supports SSD and HDD volume types"  
- "Snapshots to S3"  
- "Integrated with KMS for encryption"  
- "Multi-Attach support for io1/io2"
