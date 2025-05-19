# 📁 Amazon FSx

---

## 📌 Description  
**Amazon FSx** is a **fully managed service** that provides **file systems built on popular commercial and open-source technologies**. It enables you to run feature-rich, high-performance, and scalable file systems without the burden of managing infrastructure. AWS currently supports four types:

- 🪟 **FSx for Windows File Server**
- 📊 **FSx for Lustre**
- 🧠 **FSx for NetApp ONTAP**
- 🧬 **FSx for OpenZFS**

Each one is tailored to specific workloads and use cases.

---

## 🚀 Key Features  

### 🪟 FSx for Windows File Server  
- ✅ Built on Windows Server  
- 📂 Supports **SMB protocol**, **NTFS**, and **Active Directory integration**  
- 🔒 Offers **multi-AZ deployments** for high availability  
- 🧼 Includes **data deduplication, shadow copies, and file restoration**  

### 📊 FSx for Lustre  
- ⚡ High-throughput, **low-latency file system** for **HPC**  
- 🔗 **Integrates with Amazon S3** — syncs S3 buckets as a fast POSIX file system  
- 🧪 Best for **machine learning, analytics, genomics, and financial modeling**

### 🧠 FSx for NetApp ONTAP  
- 🧰 Includes **NetApp features** like **SnapMirror**, **FlexClone**, **multi-protocol support (SMB, NFS, iSCSI)**  
- 💾 Supports **storage efficiency** with compression and deduplication  
- 🌐 Great for **hybrid cloud and disaster recovery**

### 🧬 FSx for OpenZFS  
- 📜 POSIX-compliant **ZFS** file system with snapshots and clones  
- ⚙️ Supports **advanced Linux applications**, containers, and DevOps pipelines  
- 🛡️ Available in **single-AZ and multi-AZ** configurations

---

## 🛠️ Use Cases  

| FSx Type                 | Common Use Cases                                                                 |
|--------------------------|----------------------------------------------------------------------------------|
| **FSx for Windows**       | Home directories, Microsoft apps (e.g., SharePoint), Windows-based workloads     |
| **FSx for Lustre**        | High-speed data processing, genomics, ML model training, big data workloads      |
| **FSx for NetApp ONTAP**  | Hybrid cloud storage, disaster recovery, enterprise NAS replacement              |
| **FSx for OpenZFS**       | Linux dev environments, CI/CD pipelines, relational DBs needing ZFS features     |

---

## 🔁 Comparison with Similar Services  

| Service         | Difference from Amazon FSx |
|------------------|----------------------------|
| **Amazon EFS**   | EFS is NFS-only, Linux-focused, elastic file system; FSx offers enterprise file systems with richer features. |
| **Amazon S3**    | S3 is object storage for unstructured data; FSx supports structured file systems with protocols like SMB, NFS. |
| **Amazon EBS**   | EBS is block storage for one EC2 instance; FSx enables **shared file access** and **file system-level features**. |

---

## 💰 Pricing Overview  

💡 **Costs vary by FSx type and configuration**, but general pricing dimensions include:

- 💾 **Storage** (per GB-month):  
  - FSx for Windows: ~$0.13 (SSD)  
  - FSx for Lustre: ~$0.14 (Persistent), ~$0.025 (Scratch)  
  - FSx for ONTAP: ~$0.22 (SSD, Single-AZ)  
  - FSx for OpenZFS: ~$0.08 (SSD)

- 📈 **Throughput capacity** (optional for some types, billed per MBps-month)

- 🛡️ **Backups**: Charged per GB-month (except for Scratch Lustre)

*Note: Refer to [AWS FSx Pricing](https://aws.amazon.com/fsx/pricing/) for up-to-date info.*

---

## 🧠 Exam Keywords  
- "Fully managed file systems"  
- "FSx for Windows: SMB, AD integration"  
- "FSx for Lustre: HPC, S3 sync"  
- "FSx for NetApp ONTAP: SnapMirror, multi-protocol (SMB/NFS/iSCSI)"  
- "FSx for OpenZFS: POSIX, snapshots, cloning"  
- "Shared storage vs EBS vs EFS"  
